# Current Context Recovery — Pass 03

## Purpose
Preserve additional concrete operational and technical memories that are useful for continuity but are not yet deeply represented in the domain-owned archive. This is contextual recovery, not a transcript and not canon.

## Operational environment memories

### Android / device context
- The user has worked across Android devices and environments, including a Realme phone and an Android 15 tablet environment.
- A previously referenced tablet environment used a MediaTek MT6789-class chipset with 8 GB RAM plus virtual memory; resource limits were relevant to local AI and application experiments.
- Storage pressure and memory limits have repeatedly mattered when deciding whether an application, model, embedding system, or local tool is practical.
- The user has explored Android Accessibility Service and IME-based context injection as a way to expose external memory to arbitrary AI applications without relying on each application having native memory integration.

### Local AI constraints
- The user has considered local model execution under limited RAM/VRAM and storage rather than assuming cloud resources are always available.
- A desktop configuration discussed in prior technical planning included a Ryzen 9-class CPU, RTX 4060-class GPU, and 32 GB RAM as a target for stronger local models.
- Local-model decisions are strongly affected by model size, quantization, VRAM, RAM, context length, inference speed, and whether the capability is materially better than a hosted model.

### Storage / transport / persistence
- rclone has appeared as a practical file-transfer/synchronization tool in technical experiments.
- GitHub is treated as both a versioned transport/backup layer and an auditable history of the knowledge archive.
- Obsidian/Markdown is preferred as a durable, human-readable representation rather than a proprietary database-only format.

## Application/tool workflow memories

### Web and publishing
- WordPress was explored for a dark-themed novel website.
- Netlify was considered for static/web deployment.
- A recurring preference is for a dark, atmospheric presentation rather than a generic blog appearance.
- The user has considered building an original HTML RPG interface/site instead of depending entirely on a prebuilt narrative platform.

### Manga / reading tools
- Tachiyomi-style extension structures and JSON configuration have been explored.
- Manga/comic pages were treated as part of the creative workflow rather than merely a consumption tool.

### Automation / repository workflow
- GitHub Actions, deployment scripts, Docker files, YAML configurations, and repository-level automation have all been part of the technical workflow.
- The repository itself has become an executable historical artifact: commits record not only files but the evolution of the memory architecture.

## Model-selection and tool-selection memory

- The user does not select models solely by benchmark strength. Observed behavior, tool access, reasoning reliability, context handling, and integration constraints matter.
- The same model family can behave differently when wrappers, system prompts, proxies, routing, tool availability, or context assembly change.
- When a model behaves unexpectedly, the preferred debugging process is to inspect the entire execution chain instead of blaming the model immediately.
- When multiple models are available, parallel independent assessment can expose blind spots and reduce the risk of one model anchoring the investigation on the wrong cause.

## Integration architecture memories

- A recurring architectural distinction is:
  `source of truth` vs `access layer` vs `reasoning engine` vs `orchestration layer`.
- The durable memory should remain usable if MCP, a gateway, a plugin, a specific AI provider, or a semantic-search service disappears.
- External cognition can augment reasoning, but should not silently become the entire identity or memory of the system.
- Context injection mechanisms should provide relevant memory rather than dumping an entire vault into every request.

## Small but durable workflow preferences

- The user prefers operational answers that perform the actual operation when an available tool can do it, rather than replacing the operation with generic instructions.
- When a tool cannot perform the requested operation, the limitation should be stated precisely rather than hidden behind a simulated success.
- Large technical changes should preserve existing working elements unless the change specifically targets them.
- When investigating failures, hypotheses should stay plural until evidence narrows the field.
- When building a complex system, the user repeatedly values a strong conceptual core followed by practical implementation rather than maximal infrastructure on day one.

## Additional creative-technical intersections

- The user repeatedly merges creative and technical work: novel worlds can become web/RPG interfaces, visual identity becomes website/art direction, AI memory becomes a software architecture, and fictional system design can inform interface/game mechanics.
- These overlaps should be preserved as relationships, but similarity alone must not turn separate projects into one project.

## Evidence boundary
This file is a contextual recovery layer. Device/environment details are retained only when they have technical value for understanding past decisions. They do not constitute a complete hardware history and should not be treated as permanent personal identity data.

Historical logs, repository artifacts, source code, and original conversation exports remain stronger evidence than this reconstruction.
