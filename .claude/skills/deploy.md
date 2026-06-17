# deploy

Commit all pending changes, push to the feature branch, open a PR into `main`, and merge it so GitHub Pages updates immediately.

## Steps

1. **Stage and commit** all modified files on the current branch (`claude/blissful-shannon-pkf24e`).
   - Write a concise commit message describing what changed.
   - Use `git add <changed files>` then `git commit`.

2. **Push** the branch:
   ```
   git push -u origin claude/blissful-shannon-pkf24e
   ```

3. **Create a pull request** using `mcp__github__create_pull_request`:
   - owner: `puloxtor`
   - repo: `CampaignBeuryBoxJune`
   - head: `claude/blissful-shannon-pkf24e`
   - base: `main`
   - title: short summary of the changes

4. **Merge the pull request** immediately using `mcp__github__merge_pull_request`:
   - merge_method: `squash`

5. Confirm to the user that the changes are live and that GitHub Pages will update in ~1–2 minutes.
