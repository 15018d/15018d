# Hello World

```c
typedef struct {
    const char *name;
    const char *role;
    const char *site;
    bool        open_to_work;
} person_t;

static const person_t me = {
    .name         = "Bogdan",
    .role         = "Software & Security Engineer",
    .site         = "https://isol8d.ru",
    .open_to_work = true,
};

static const char *stack[] = {
    "C", "Go", "C++", "PHP", "Python",
    "Linux", "Docker", "Git", "PostgreSQL", "MySQL", "Oracle",
    NULL
};
```
