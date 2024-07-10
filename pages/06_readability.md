# Readability

- selectors
- test annotation

````md magic-move
```js
// ❌ don’t do it like this
it('board is visible', () => {})
it('works in edge cases', () => {})
it('handles input', () => {})
```

```js
// ✅ much better
it('creates a board and navigates to board detail', () => {})
it('throws error when trying to access private board', () => {})
it('shows a warning message when input is empty', () => {})
```
````
- documentation

<style>
.slidev-layout li {
  font-size: 1.7rem;
}
.slidev-layout ul {
  padding-top: 10px
}
</style>

<!--
- why readability - because when you write a complex test that does a very complex thing and it finally passes, it feels like a victory. until you need to open that test again and debug what’s wrong. there’s a reason why developer have peer reviews and focus on writing good code - no one wants to refactor or add functionality to garbage code, because they are afraid something will break
- selectors can be a big part of readability
- approaches
  - data-id
  - accessibility selectors
  - everything else
  - you can combine approaches, it’s fine

- why readability - ultimately readability is about being able to do things around a project fast, so by providing good documentation you can help that a lot
### documentation
Usually the documentation contains 3 important parts:
- installation of the projects
- explanations, recommendations, examples
- pull request rules (these can be added to the platform you use)
-->
