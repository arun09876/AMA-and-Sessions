# AMA Questions and Answers

## 1. Difference between `pop()` and `remove()`?

`pop()` removes an element using index and returns the removed value.  
`remove()` removes an element using its value.

Example:
```python
a = [10, 20, 30]

a.pop(1)
a.remove(10)
```

---

## 2. What is GitHub?

GitHub is a cloud-based platform used to store and manage Git repositories online.  
It helps developers collaborate, track changes, and maintain code versions.

---

## 3. Difference between Git, GitHub, and GitLab?

- Git → Version control system used locally.
- GitHub → Online hosting platform for Git repositories.
- GitLab → Git hosting platform with DevOps and CI/CD support.

---

## 4. Delete remote branch reference in local?

```bash
git fetch --prune
```

This removes deleted remote branch references from the local repository.

---

## 5. Difference between `/`, `/root`, and `sudo -i`?

- `/` → Root directory of Linux filesystem.
- `/root` → Home directory of root user.
- `sudo -i` → Switches to root user shell.

---

## 6. Disconnect local git from remote GitHub URL?

```bash
git remote remove origin
```

This removes the connection between local repository and remote repository.

---

## 7. See audio driver of system?

```bash
lspci | grep -i audio
```

Displays audio hardware and driver information.

---

## 8. See CPU details?

```bash
lscpu
```

Shows CPU architecture, cores, threads, and processor details.

---

## 9. Difference between `git status` and `git log`?

- `git status` → Shows current modified or untracked files.
- `git log` → Shows commit history.

---

## 10. Use of cherry-pick?

```bash
git cherry-pick <commit-id>
```

Copies a specific commit from one branch to another branch.

---

## 11. Use of `git reset`?

```bash
git reset --hard HEAD~1
```

Used to undo commits or remove staged changes.

---

## 12. Difference between list and dict?

- List → Ordered collection using indexes.
- Dictionary → Collection of key-value pairs.

Example:
```python
a = [1, 2, 3]

b = {
    "name": "Arun"
}
```

---

## 13. Difference between `append()` and `extend()`?

- `append()` adds a single element.
- `extend()` adds multiple elements from another iterable.

Example:
```python
a = [1, 2]

a.append(3)

a.extend([4, 5])
```

---

## 14. Difference between parent and child process?

- Parent process creates another process.
- Child process is the newly created process.

---

## 15. Difference between `git pull` and `git fetch`?

- `git fetch` → Downloads latest changes only.
- `git pull` → Downloads and merges changes automatically.

Example:
```bash
git fetch origin

git pull origin main
```
