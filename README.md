# action-pixela-increment
GitHub Action to increment pixela graph.

![pixela](https://pixe.la/v1/users/mike-neck-hatenadiary-com/graphs/gh-action-test)

Inputs
---

- `user`
    - A User name.
- `graph-id`
    - An id of a graph being incremented.
- `token`
    - A token of the user.

Outputs
---

No outputs.

Example
---

```yaml
        - name: run test
          uses: mike-neck/action-pixela-increment@master
          with:
            user: mike-neck-hatenadiary-com
            graph-id: gh-action-test
            token: ${{ secrets.PIXELA_TOKEN }}
```

