# kazakh-text-to-gloss
Kazakh Natural Text → Kazakh Sign Language Gloss (JSON)


## Қазақша
Бұл репозиторийде **қазақ тіліндегі табиғи мәтінді** **қазақ ым тіліне (gloss)** айналдыратын JSON деректер сақталған. Дерек **text-to-gloss** моделін оқыту/валидациялау үшін қолданылады.

### Негізгі идея
- Кіріс: табиғи қазақша сөйлем/сұрақ/анықтама  
- Шығыс: Kazakh Sign Language gloss (қысқа, стандартталған бірліктер)

Мысал:
```json
{
  "Жердің төрт қабығы бар.": "ЖЕР 4 ҚАБЫҚ БАР"
}
```
## English
This repository contains JSON mappings from **natural Kazakh text** to **Kazakh Sign Language gloss**.  
The dataset is intended for training and evaluating **text-to-gloss** models.

### Concept
- Input: natural Kazakh sentences/questions/definitions  
- Output: KSL gloss sequence (standardized tokens)

Example:
```json
{
  "Жердің төрт қабығы бар.": "ЖЕР 4 ҚАБЫҚ БАР"
}
```
