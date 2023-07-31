## Graphics
<details>
<summary>./svg</summary>

| Thumbnail | Image |
| --------- | ----- |
| <img src="./svg/DU_logo_Color.svg" alt="DU_logo_Color.svg" width="100"> | [DU_logo_Color.svg](./svg/DU_logo_Color.svg) |
| <img src="./svg/DU_logo_White.svg" alt="DU_logo_White.svg" width="100"> | [DU_logo_White.svg](./svg/DU_logo_White.svg) |
| <img src="./svg/doug-rocket.svg" alt="doug-rocket.svg" width="100"> | [doug-rocket.svg](./svg/doug-rocket.svg) |
| <img src="./svg/favicon.svg" alt="favicon.svg" width="100"> | [favicon.svg](./svg/favicon.svg) |
| <img src="./svg/navbar-logo.svg" alt="navbar-logo.svg" width="100"> | [navbar-logo.svg](./svg/navbar-logo.svg) |
</details>


### How to use the pre-commit hook

<details>

Note: If you make any changes to the pre-commit script, be sure to commit and push the changes to the repository so that other contributors can benefit from the updated functionality.

1. Run the following command to set up the pre-commit hook:
   ```bash
   cp pre-commit .git/hooks/pre-commit
   ```

2. Make the pre-commit script executable by running the following command in the root of your local clone:
   ```bash
   chmod +x .git/hooks/pre-commit
   ```

3. Now, whenever you make a commit, the pre-commit hook will automatically generate the README.md file with Graphics lists including thumbnails.

</details>

