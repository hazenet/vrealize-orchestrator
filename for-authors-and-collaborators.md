# For authors and collaborators

## Comments, ideas and inputs {#comments-ideas-inputs}

## Become a collaborator {#become-a-collaborator}

## Structure {#structure}

All chapters should be placed in the root folder of the Github\/Gitbook project.

All images should be placed in the \/assets\/ folder, to try and keep it somewhat organized.

In the SUMMARY.md file, the "Table of Contents" is build up.

Chapter files should be referenced first, like this:

```
* [What is vRealize Orchestrator](what-is-vrealize-orchestrator.md)
```

H2 headings in each chapter should be referenced manually, by doing the following on a indented line below each chapter:

```
    * [Origin](what-is-vrealize-orchestrator.md#origin2)
```

For this to work, it is needed to create a Markdown anchor after each H2 heading in the actual chapter file. So a H2 heading in the "What is vRealize Orchestrator.md" file would look like this:

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

Because this will be a continuously written book, we can't have "Fig. 1.3" references was one would normally have in a book.

So to overcome that issue, I have decided to use short random generated reference-ids instead. That way it does not matter when a perticular images was added to a chapter, and a chapter may be injected anywhere in the book at any time.

I suggest that we use [Random.org's random sting generator](https://www.random.org/strings/), with length set to 4 characters and to include Numerics and Uppercase leters only. That would give us a maximum of 1.679.616 images or screenshots, which should be enough by my estimates.

These settings would generate a random string looking like this sample:

```
HJR5
```

The actual image or screenshot would the be named with this random string, like the following:

```
HJR5-some-descriptive-name.png
```

Before added a image or screenshot to the book, please resize the image so that it has a max width of 1.000px

![HJR5 - Random.org](/assets/HJR5-random-org.png)

When a random string has been generated, please do a search in the book before using it, to verify that it has not been used before. A repeat of a random generated string might still occur, so we will have to manually verify the uniqueness before using it.

The easiest way to do a search in the complete book would be to go to [online reader of the book](https://www.gitbook.com/read/book/hazenet/vrealize-orchestrator) and use the search option in the top-left corner.

When adding a image to the book, using the following text-syntax:

```
![HJR5 - Random.org](/assets/HJR5-random-org.png)
```

The first part is the Title of the image, which will be automatically added as caption beneath the image, when the book is build via Gitbook:

```
Figure HJR5 - Random.org
```

## Attachments and code files {#attachments-and-code-files}



