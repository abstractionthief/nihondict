nihondict

A personal, structured dictionary of Japanese vocabulary extracted from paper books I own.

This repository contains a curated dataset of Japanese words and expressions collected during reading.
Each entry is normalized, categorized, and annotated with usage notes, register, and learning status, making the data suitable for review, filtering, and further integration (e.g. CSV tools, Anki, or custom scripts).

The CSV file is the single source of truth; all other views or tools are derived from it.

graph TD

core --> core_basic["core.basic"]
core --> core_grammar["core.grammar"]

social --> social_greetings["social.greetings"]
social --> social_expressions["social.expressions"]
social --> social_fixed["social.fixed"]
social --> social_introduction["social.introduction"]
social --> social_relationships["social.relationships"]
social --> social_family["social.family"]

actions --> actions_daily["actions.daily"]
actions --> actions_motion["actions.motion"]

descriptions --> descriptions_basic["descriptions.basic"]
descriptions --> descriptions_colors["descriptions.colors"]
descriptions --> descriptions_quantities["descriptions.quantities"]

objects --> objects_places["objects.places"]
objects --> objects_communication["objects.communication"]

education --> education_institutions["education.institutions"]
education --> education_people["education.people"]

geography --> geography_countries["geography.countries"]

language --> language_basic["language.basic"]

numbers --> numbers_basic["numbers.basic"]

time --> time_basic["time.basic"]
time --> time_clock["time.clock"]

person --> person_self["person.self"]
person --> person_identity["person.identity"]

occupations --> occupations_professions["occupations.professions"]

abstract --> abstract_emotions["abstract.emotions"]
