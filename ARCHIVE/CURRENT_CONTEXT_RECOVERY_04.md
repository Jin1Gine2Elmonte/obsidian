# Current Context Recovery — Pass 04

## Purpose
This pass captures additional durable context that is easy to lose because it sits outside the main fiction and agent-architecture threads. It is a recovery layer, not a transcript and not a canonical source.

## Evidence boundary
Source class: accessible durable context and prior-conversation summaries available in the current session.
Historical transcript exports outrank this layer. Items remain context-level unless their source and project/version are independently verified.

---

# I. Reading / research interests

- Recurring interest areas include AI and technology; literature and writing; philosophy and psychology; and politics/geopolitics as subjects of research and reading.
- A preferred long-form reading workflow was established around finding a substantial free/accessible article or essay published recently, ideally with a reading time in the roughly 25–45 minute range.
- The user values not just recommendations but an explanation of why a text is worth the time and how it connects to ongoing interests.
- Contemporary AI research is often approached as an evolving technical landscape rather than a static body of facts; freshness matters when model behavior, tools, releases, or providers can change.
- Deep research is preferred over shallow list-making when a topic has multiple interacting causes, architectures, or competing interpretations.

# II. Research / investigation style

- When a technical or conceptual failure has several plausible causes, the preferred method is to preserve multiple hypotheses and test them rather than prematurely selecting one explanation.
- Parallel model or independent-review approaches have been requested for difficult debugging and architecture analysis.
- Research should distinguish source evidence from model synthesis, and current-state claims from historical claims.
- The user is sensitive to answers that sound confident while merely extrapolating from sparse evidence.
- A useful research output should expose uncertainty, unresolved branches, and what evidence would discriminate between competing explanations.

# III. Naming / translation / terminology

- The user has explored distinctions between the lexical meaning of an Arabic word and its use as a proper name when translating or transliterating into English.
- A remembered example concerned “خالد / Khalid”: the semantic idea of permanence/endurance versus the proper-name form “Khalid” should not be conflated.
- Fictional naming is treated as part of world identity, sound, atmosphere, and characterization rather than as decoration added after the fact.
- Project titles and character names may evolve; the archive should record aliases, replacements, translations, and generation-specific names when evidence becomes available.

# IV. Web / platform / personal-project history

- WordPress was explored as a way to host a dark-themed novel/fiction website.
- Netlify appeared in deployment/site discussions.
- Novel-site design repeatedly favored dark, atmospheric presentation rather than generic blog aesthetics.
- HTML/RPG website ideas were explored, including systems inspired by progression-fantasy mechanics.
- React/Firestore concepts appeared as an application architecture direction.
- Tachiyomi and extension/JSON structures were explored in connection with manga-reading workflows.
- Repository automation, structured YAML/Markdown files, Docker, and GitHub Actions became part of the broader project workflow.

# V. Tool-use behavior / workflow preferences

- When an operational tool exists, the preference is that the tool perform the real operation rather than replacing it with generic instructions.
- When a tool is unavailable, the limitation should be identified precisely and the architecture should be investigated rather than pretending the unavailable operation occurred.
- The user often prefers a high-effort exploratory pass before settling on an implementation, especially for agent architecture, memory systems, and debugging.
- Repeated correction has established a strong preference for preserving the actual work history instead of rewriting the final result as though the path was always obvious.
- The user dislikes “more words” that do not produce new information, new constraints, new relationships, or a better decision.

# VI. Model / provider investigation habits

- The user has compared ChatGPT, Gemini, DeepSeek, GLM-family models, Nemotron-family models, and other systems as practical tools rather than merely as benchmark labels.
- The user has paid attention to behavioral differences between models even when they appear to run in the same environment.
- Possible causes considered in past work include system prompts, hidden/degraded context, tool availability, proxy behavior, request routing, provider wrappers, model configuration, and runtime differences.
- The preferred troubleshooting posture is to keep these causes distinct until evidence connects them.
- The user has used or considered parallel model evaluation as a way to avoid trusting one model's first explanation.

# VII. Cross-model continuity ambitions

- The user wants durable knowledge to remain coherent while moving among ChatGPT, Gemini, Qwen, and other AI systems.
- A core concern is avoiding provider lock-in: the underlying knowledge should remain portable while prompts, adapters, MCP tools, gateways, and model-specific interfaces can change.
- Obsidian/Markdown is intended to provide a human-readable and model-independent substrate.
- Retrieval systems are expected to assemble relevant context instead of dumping the entire archive.
- The user has explored ways to inject context automatically into AI applications through Android accessibility and IME-related mechanisms.

# VIII. Small creative / visual workflow fragments

- Image and cover revisions frequently use “surgical edit” constraints: change exactly the requested property while preserving unrelated approved properties.
- Visual qualities that recur include atmospheric depth, carefully controlled lighting, translucency, restrained color accents, negative space, narrative composition, and a desire to avoid generic AI artifacts.
- Character image work has included anime/manhwa aesthetics, full-body reconstruction, manga/comic panels, and sequential pages.
- A remembered page-generation correction involved removing an unintended Ghibli-like drift and restoring a style closer to the intended source-series visual identity.
- The user frequently treats the image as a pre-existing composition with invariants, not as a blank prompt that grants the model freedom to redesign everything.

# IX. Audio / music fragments

- AI song generation has been explored through prompt design rather than only direct generation.
- A specific remembered use case involved a song prompt for a girlfriend, with attention to emotional atmosphere and sense of place.
- Voice/audio-generation tools are part of the broader creative-tool ecosystem.
- Full histories of song prompts, revisions, and audio outputs remain unrecovered.

# X. Small fiction / RPG / system-design fragments

- Progression-oriented RPG concepts have been explored using inspirations such as Solo Leveling and Nano Machine while aiming to create an original system rather than reproduce source mechanics.
- HTML/RPG site concepts combine game systems with dark world atmosphere and presentation.
- Game/system mechanics should serve the fiction's needs; inspiration does not automatically become canon or a required mechanic.
- The archive should eventually distinguish “inspiration,” “prototype mechanic,” “tested mechanic,” and “final project rule.”

# XI. Practical technical history fragments

- Historical deployment work included Fly.io, Northflank, Oracle Cloud, Docker, GPU hosting, rclone, and GitHub Actions.
- A remembered Fly.io limitation stated that the organization was limited to 4 CPU cores per machine.
- Hermes deployments involved Docker/YAML/configuration, storage, embeddings, and tool constraints.
- NEXUS architecture discussions included an Omni-Server concept, orchestration, MCP, external cognition, routing, and a separation between an external reasoning layer and a distinct internal/autonomous core.
- Memory architecture discussions repeatedly returned to exact retrieval, semantic search, graph traversal, embeddings, provenance, and maintaining the vault when a provider or access layer disappears.

# XII. Device / environment context relevant to technical experiments

- The user's technical experiments have included Android environments, constrained phone/tablet hardware, local-model feasibility, and consideration of stronger desktop hardware for local AI.
- Hardware constraints have repeatedly influenced architecture decisions, especially around RAM, storage, model size, GPU feasibility, and what can realistically run locally.
- This context should be treated as historical operating context, not as permanent identity or an invariant hardware specification.

# XIII. Creative identity / practice signals outside the main fiction nodes

- The user prefers original mythological systems rather than obvious cultural imitation.
- The user often begins from intuition and a large conceptual nucleus, then asks for deep structural analysis to turn the nucleus into executable form.
- The user values details that alter meaning rather than decorative detail.
- The user repeatedly asks for “what is the actual purpose of this element?” before adding it to a larger system.
- A recurring tension in creative work is between immense conceptual ambition and the need for readable, moving, emotionally grounded scenes.
- The user wants continuity across domains: creative, technical, research, and systems work should share a coherent deeper identity while allowing local style to adapt.

# XIV. Meta-history of collaboration

- The user has repeatedly corrected the assistant when a compressed memory summary was treated as the complete history.
- This has become a defining constraint of the current archive work: summaries are maps, not the territory.
- The user expects the assistant to continue searching for new paths when a useful layer has been exhausted rather than repeatedly paraphrasing the same layer.
- The user places a high value on revisiting previous work with stronger analysis and correcting the architecture itself when its assumptions become inadequate.
- The archive project therefore doubles as a record of how the collaboration's reasoning and memory practices evolved.

# XV. Research / learning continuity

Potential durable study/research threads include:
- frontier and open AI systems;
- agent architecture and tool use;
- memory and knowledge systems;
- literary craft and narrative engineering;
- philosophy/psychology of identity, reality, memory, and forgetting;
- current geopolitical and political research as a subject area;
- long-form essays and substantial free reading.

The specific source history, books/articles, conclusions, and research rabbit holes remain under-recovered.

# XVI. Recovery boundary

This pass intentionally captures small, cross-domain memories that are easy to overlook. It must not be read as evidence that these details were reconstructed from exact historical transcripts. The next layer should attach dated conversation passages, artifacts, prompts, source links, or repository evidence wherever available.
