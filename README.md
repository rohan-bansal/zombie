# Zombie

Zombie is a minimalist [ghost](https://ghost.org/) theme for code-accustomed eyes. Heavily inspired by [ganymede](https://github.com/itsmingjie/ganymede). Demo [here](https://blog.rbansal.dev).

## Configuring Routes

Modify the `routes.yaml` to contain the following:

```yml
routes:
  /archives/: 
    template: archives


collections:
  /:
    permalink: /{slug}/
    template: index

taxonomies:
  tag: /tag/{slug}/
  author: /author/{slug}/
```

