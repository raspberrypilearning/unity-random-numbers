Use `Random.Range(min, max)` to generate random numbers within a range. 

For example, you could make a GameObject move to a specific position:

--- code ---
---
language: cs
---
void Start()
{
   transform.position = new Vector3(Random.Range(-10.0f, 10.0f), 1, Random.Range(-10.0f, 10.0f));
}
--- /code ---

