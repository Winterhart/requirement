# Agile Classic

Classic way requirements are done in Scrum Methodology.

## Elements

Doing requirements with agile is often about the elements. Based on the situation,
the requirement should be extracted to an element.

The difficulty for product owner/project manager is often to
known which requirements is what: *Epic*, *Story*, *Task*, *Spike*...


### Epic

An *Epic* is a story of stories to capture multiple use cases in one idea.
Usually, we can get few stories out of an *Epic*. 

The difficulty here is to find the right size. Usually, if you can find multiple-use case/scenario
in a story it's an *Epic*!

If you can find one scenario only maybe it's a large story.

e.g.

The customer can pay items on his card. => EPIC

---

Registering your pet to the clinic failed => STORY

---

Allow the owner to register their pets to the clinic => EPIC

---

### Story

The story should be written in the good old format:

---

As a *persona*, I want *goal* so that *consequence*

---


e.g. 

```

As a pet owner, I want to be able to register my pet so
that the clinic can assign me a specialist.

```



### Theme (optional)

Some folks use the word *Theme* to describe a group of
*Epic* together. 



### Task (optional)

Often, from a story should be seen as multiple parts that once
connected forms a feature.

If you are using good old web enterprise application architecture, you can
divided your task per layer.

e.g.

```
Story: As a pet owner I want to successfully book an appointment in a web calendar
so that my pet can get an appointment.

Tasks:
- Add appointment table (SQL)
- Add appointment repository or TDG/Finder...
- Add appointment in the domain layer
- Add appointment feature
- Create front-end calendar
- [...]
```
### Spike 

A time-boxed event by which a developer attempts to resolve an issue or
simply integrate a new technology to the product.

e.g.

```

Can we saved the client records using block chain technology?

```

## Sources

- https://goodpatch.com/blog-en/wp-content/uploads/epics-vs-stories-agile-development-768x399.png