# Data Model (planned)

## prompt_sets - (Default settings)

- id, name, version, status, created_at
- source: "built_in" | "imported" | "generated"
- export_json: jsonb (optional convenience)

## prompts / prompt_options

- unchanged core structure

## sessions

- id, prompt_set_id, status, policy_json, share_token
- mode: "single" | "collaborative"

## responses

- include respondent_id (nullable in MVP; used for collaborative)
- session_id, prompt_id, choice, fields...

## derived_results

- can be computed per respondent and/or per session cohort (policy dependent)
