# ViaRE's Reference

This is the place in where we share the list of references we use to keep developing
[ViaRE](https://github.com/daque-dev/viare).

This includes both:
1. books that will be directly used as reference for new integrations into ViaRE, and
1. books that help Daque members become better developers (or persons).

## Content
- [The proccess](#the-proccess) (how to add more references to this repo)

## The proccess

Every reference we find must go through this proccess:

### The Finding
    
We find a book, website, article, magazine, etc. that we consider
may be useful to keep generating ideas, getting context, or keeping us interested.

If the book could be used to generate ideas for ViaRE, it will be added to 
`/viare/to-read.md`. 
Otherwise, it will be added to `/to-read.md`

When we skim the table of contents or something similar, we should take note of what
the book could provide us.

### Note-taking

When any member or contributor of [Daque](https://github.com/orgs/daque-dev/people)
starts to read an item inside `/to-read.md` or `/viare/to-read.md`, they must start
to take notes on that item. 

To start taking notes, you create a file inside `/reading` or `/viare/reading`. 
The name of the file will be `{Author's Surname}{Year} - {Title}.tex`. If that file
already exists, it must mean that someone already started taking notes. In such case,
you should add your name as a subtitle at the end of the file, and start taking notes in there.

Example filenames:

- `/reading/Kleinberg2005-Algorithm-design.tex`
- `/viare/reading/Ilachinski2004-Artificial-war.tex`

---

A note must be added to the book entry in `/to-read.md` or `/viare/to-read.md` indicating your name and the date you started reading it in format YYYY-MM-DD. For example:

`- {Book entry} | David, 2019-02-20`


### Finished books

When any book is finished by any member, they must move their notes to `/notes` or 
`/viare/notes`, and remove them from `/reading` or `/viare/reading`. 

The last member to finish the book, should remove the book entry entirely from `reading`.

### Referencing notes

Every file inside `/notes`  or `/viare/notes` must be referenced from this file, under
the category (or categories) it fits better in. If no category seems appropiate, it
should be discussed in a new issue. A brief paragraph must accompany the entry, and
must describe the most general contribution to this knowledge-base.

## Notes

### /

#### Development

- **{Book title with link to entry in `/notes`}**: {Brief description of the content}

#### Mathematical Thinking

- **{Book title with link to entry in `/notes`}**: {Brief description of the content}

### /viare

#### Geography

- **{Book title with link to entry in `/viare/notes`}**: {Brief description of the content}

#### Evolution

- **{Book title with link to entry in `/viare/notes`}**: {Brief description of the content}
