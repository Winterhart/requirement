# Agile Classic

Classic way requirements are done in Scrum Methodology.

## Elements

Doing requirements with agile is often about the elements. Based on the situation,
the requirement should be extracted to an element.

The difficulty for product owner/project manager is often to
known which requirements.


### Epic

An *Epic* is a screenshot to capture multiple use cases in one idea.
Usually, we can get few stories out of an *Epic*. 

Difficulty here is the size. Usually, if you can find multiple use case/scenario
in an *Epic* it's an *Epic*.

If you can find one scenario only maybe it's a large story.

e.g.

The customer can pay items on his card. => EPIC

---

Registering your pet to the clinic failed => STORY

---

Allow owner to register their pets to the clinic => EPIC

---

### Story

The story should be written in the good old format

---

As a *persona*, I want *goal* so that *consequence*

---


e.g. 

```

As a pet owner, I want to be able to register my pet so
that the clinic can assign me a specialist.

```



### Initialtive/Theme (optional)

Some folk uses the work *Theme* or *Initiative* to describe a group of
*Epic* together. 



### Task (optional)

Often, from a story it's should be seen as multiple parts that once
connected together forms a feature.

If you are using good old web enterprise application architecture, you can
divided your task per layer.

e.g.

```
Story: As a pet owner I want to successfully book an appointment in a web calendar
so that my pet can get an appointement.

Tasks:
- Add appointment table (SQL)
- Add appointment repository or TDG/Finder...
- Add appointment in domain layer
- Add appointment feature
- Create front-end calendar
- [...]
```
### Spike 

## Sources

- https://goodpatch.com/blog-en/wp-content/uploads/epics-vs-stories-agile-development-768x399.png