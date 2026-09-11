# TARGET: today's build

Choose the idea, person, interaction, and visual direction. The agent can help phrase and save your decisions after you approve them. The provided scope and review safeguards stay in place.

- **Thing:** A one-page beginner cooking guide where a visitor enters or selects a supported meal and receives its ingredients, numbered instructions, and essential cooking rules.
- **Audience:** College students living independently who have little cooking experience and want clear guidance without assumed kitchen knowledge.
- **Requirements:** Provide one obvious meal-search interaction; support a curated set of eight familiar, college-friendly meals—scrambled eggs, grilled cheese, quesadillas, pasta with tomato sauce, fried rice, baked potatoes, pancakes, and oven-baked chicken; let users adjust each recipe from one to four servings; show recalculated ingredient quantities, required equipment, numbered instructions, approximate timing, and clearly labeled safety or doneness guidance; when a meal is unavailable, say so and suggest supported alternatives rather than inventing a recipe.
- **Guardrails:** Static browser code. No required external service, keys, accounts, runtime AI, or private data. Label fictional or sample content. Preserve the example and publishing setup. Work on a branch and wait for human review before shipping.
- **Experience:** Clean, chic, and understated, with strong typography, generous spacing, refined neutral colors, and short purposeful transitions. Results should remain easy to scan on a phone, with keyboard-operable controls, visible focus, readable contrast, and reduced-motion support.
- **Test:** I can enter a supported meal, adjust it from one to four servings, and receive correctly scaled ingredient amounts plus complete equipment, numbered instructions, timing, and safety or doneness guidance; enter an unsupported meal and receive honest alternatives; use the interaction by keyboard on a narrow screen; and point to the standing rule's effect in the preview. After I approve and merge, the same registered Pages URL works.

The coastal example has a [completed TARGET](examples/coast/SPEC.md). It demonstrates the format, not a required topic.
