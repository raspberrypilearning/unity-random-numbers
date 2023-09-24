Gebruik `Random.Range(min, max)` om willekeurige getallen binnen een bereik te genereren.

Je kunt bijvoorbeeld een GameObject laten verplaatsen naar een specifieke positie:

--- code ---
---
language: cs
---

void Start()
{ transform.position = new Vector3(Random.Range(-10.0f, 10.0f), 1, Random.Range(-10.0f, 10.0f)); }

--- /code ---

