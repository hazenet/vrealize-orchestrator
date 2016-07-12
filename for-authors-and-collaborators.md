# For authors and collaborators

## Comments, ideas and inputs {#comments-ideas-inputs}

## Become a collaborator {#become-a-collaborator}

## Structure {#structure}

All chapters should be placed in the root folder of the Github\/Gitbook project.

All images should be placed in the \/images\/ folder, to try and keep it somewhat organized.

In the SUMMARY.md file, the "Table of Contents" is build up.

Chapter files should be referenced in first, like this:

```
* [What is vRealize Orchestrator](what-is-vrealize-orchestrator.md)
```

H2 headings in each chapter should be referenced manually, by doing the following on a indented line below each chapter:

```
    * [Origin](what-is-vrealize-orchestrator.md#origin)
```

For this to work, it is need to create a Markdown anchor after each H2 heading in the actual chapter file. So a H2 heading in the "What is vRealize Orchestrator.md" file would look like this:

```
## Origin {#origin}
```

## Chapter file naming {#chapter-file-naming}

Chapters should be named with a relevant title, and the file should have the exact same name as the title. Chapter file names should be in all lowercase, and with spaces replaced by dashes.

Sample title:

```
#Some relevant title
```

Sample chapter filename:

```
some-relevant-title.md
```

## Image naming and referencing {#image-naming-and-referencing}

## Attachments and code files {#attachments-and-code-files}

