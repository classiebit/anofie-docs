# Multiple Languages

Anofie supports multiple languages, including Russian, Portuguese, Chinese, Japanese and even RTL languages such as Arabic, Persian, Urdu, etc. 

---

![multi-language](https://anofie-docs.classiebit.com/images/multi-language.jpg "multi-language")

---

> {success} Anofie `Auto-detects` **RTL** language and changes the website direction to **RTL**

---

- [Add New Language](#Add-New-Language)


<a name="Add-Language"></a>
## Add Language

All the language files can be found in `application/language` directory. To add a new language, simply copy the `english` directory and paste it as `<your_language_name>`. Then translate all the files inside the new language folder.

---

>{warning} Translate variable **VALUES** only and not **VARIABLE NAMES**

---

> {info} Recommended file to translate- `core_lang`

---

e.g Suppose you wanna add `mandarin` language. Simply copy the `english` folder and paste it as `mandarin`.

```bash

    application
        │
        ├── language
            ├── english
            └── mandarin

```