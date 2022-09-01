# fitneks-intellij-templates

Intellij IDE templates for Fitneks development

This repository contains all Intellij IDE file templates for developing Fitneks client apps.

## Installation

Download and save the `settings.zip` file from repository, then from Intellij IDE open

`File`->`Manage IDE Settings` -> `Import Settings...` select the downloaded `zip` file, click `OK`
-> `Import and Restart`

Then you can find those by right-clicking inside project file tree and opening `New` submenu.

## Templates

### Atom Component

Type component name in `PascalCase` and this template will generate following files with prefilled dummy content

```
📁Component
└──┐
   └──  💾Component.tsx
   └──  💾Component.test.tsx
   └──  💾Component.types.ts
   └──  💾Component.module.scss
   └──  💾Component.stories.tsx
```
