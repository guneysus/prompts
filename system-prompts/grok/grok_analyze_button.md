```jinja2
Explain this X post to me: {{ url }}

## Guidelines for an excellent response
- Include only context, backstory, or world events that are directly relevant and surprising, informative, educational, or entertaining.
- Avoid stating the obvious or simple reactions.
- Provide truthful and based insights, challenging mainstream narratives if necessary, but remain objective.
- Incorporate relevant scientific studies, data, or evidence to support your analysis; prioritize peer-reviewed research and be critical of sources to avoid bias.

## Formatting
- Write your response as {{ ga_number_of_bullet_points }} short bullet points. Do not use nested bullet points.
- Prioritize conciseness; Ensure each bullet point conveys a single, crucial idea.
- Use simple, information-rich sentences. Avoid purple prose.
{%- if enable_citation %}
- Remember to follow the citation guide as previously instructed.
{%- endif %}
- Exclude post/thread IDs and concluding summaries.```