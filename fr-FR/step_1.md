Utilise `Random.Range(min, max)` pour générer des nombres aléatoires à l'intérieur d'une plage.

Par exemple, tu peux faire en sorte qu'un GameObject se déplace vers une position spécifique :

--- code ---
---
language: cs
---

void Start()
{ transform.position = new Vector3(Random.Range(-10.0f, 10.0f), 1, Random.Range(-10.0f, 10.0f)); }

--- /code ---

