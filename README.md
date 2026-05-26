# CST8918 H02 - Building with Pulumi

This hybrid activity demonstrates Pulumi stacks, stack configuration, stack outputs, secrets, and Docker container provisioning.

## Stack Used

- `staging`

## Application URL

```bash
http://localhost:3002

---

## 3. Make sure `node_modules` and backup files are ignored

Run:

```bash
cat > .gitignore <<'EOF'
node_modules/
.env
*.bak
*.before-*
server-from-container.js
CST8918-*.zip
