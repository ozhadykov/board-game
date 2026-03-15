# Island Family Survival
This is a Tauri based Web game, built upon ideas of some smart small kids.

## Commit Conventions

To maintain a clean and readable history, please use the following prefixes for your commit messages:

| Prefix | Use Case | Example |
| :--- | :--- | :--- |
| **`feat:`** | Adding a new feature or capability. | `feat: add dice rolling animation` |
| **`fix:`** | Fixing a bug or unexpected behavior. | `fix: prevent player from moving twice` |
| **`refactor:`** | Improving code structure without changing behavior. | `refactor: extract board logic into a custom hook` |
| **`chore:`** | Maintenance tasks (updating dependencies, config). | `chore: update tauri to v2.1.0` |
| **`docs:`** | Documentation only changes. | `docs: add setup instructions to README` |
| **`style:`** | UI/UX styling (CSS/Tailwind) or code formatting. | `style: improve board contrast for accessibility` |
| **`test:`** | Adding or correcting tests. | `test: add unit test for win condition logic` |
| **`perf:`** | Code changes that improve performance. | `perf: optimize board rendering with React.memo` |
| **`rust:`** | Changes specifically in the `src-tauri` backend. | `rust: implement sqlite save command` |

### Guidelines
- **Format:** `prefix: description`
- **Subject:** Use the imperative mood (e.g., "add", not "added").
- **Body (Optional):** Use to explain *why* the change was made if it's complex.
