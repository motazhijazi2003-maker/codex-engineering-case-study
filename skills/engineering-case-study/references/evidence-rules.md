# Engineering evidence rules

## Proposals and simulations

- A proposal establishes intent, not a completed outcome.
- Planned solver or mesh studies do not establish that simulation ran or mesh independence was achieved.
- Report simulation operating conditions and available verification. Missing checks limit confidence.
- Percentage improvements need a baseline and matched conditions. Identify missing denominators or mismatched setups.
- Individual contribution requires explicit evidence; filenames alone are insufficient.

## Energy calculators

- Inspect input/output labels and formulas together. Distinguish energy (kWh) from power (kW).
- Label solar resource, efficiency, electrolyzer specific energy, and emissions factors as assumptions. Constants in code are not current local benchmarks.
- Reproduce representative cases and relevant supported boundaries; explain output rounding.
- Grid displacement and hydrogen production may represent alternative uses of the same electricity. Do not add both avoided-emissions benefits without an allocation and counterfactual.
- Arithmetic checks do not validate weather, equipment, browser rendering, or measured environmental impact.

## Writing

Use "the model estimates" for model outputs and "testing measured" only for documented measurements. Source statements are not automatically independently verified facts. Research external performance claims when needed using technical primary sources. Omit personal contact details from public examples.
