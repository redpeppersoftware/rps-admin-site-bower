#Purpose

Provide a quick way to pull in all dependencies used by sites generated using the rps-admin-site-generator.

#Usage

```
"rps": "redpeppersoftware/rps-admin-site-bower"
```

Bower will find this dependency by its github url.

Full `bower.json`:

```
{
  "name": "some-project-admin-site",
  "private": true,
  "version": "1.0.0",
  "authors": [
    "Red Pepper Software"
  ],
  "description": "some project description",
  "dependencies": {
    "rps": "redpeppersoftware/rps-admin-site-bower#v1.0.0"
  }
}
```

> Be sure to add some sort of tag (such as `#v1.0.0`) to the dependency to ensure your app works in the future.
