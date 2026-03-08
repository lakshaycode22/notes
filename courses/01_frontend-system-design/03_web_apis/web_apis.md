### Intersection Observer

```typescript
const observer = new IntersectionObserver(
  (entries) => {
    entries.forEach((entry) => {
      //code
    });
  },
  { threshold: 0.1, root: rootElement },
);
observer.observe(targetElement);
```
### Mutation Observer