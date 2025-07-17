# TIL — Today I Learned...✏️


Today, I learned how to make my GitHub profile stand out more effectively.

✔ I discovered a great resource for icons to enhance my profile visually.

✔ Before editing the `README.md`, you need to create a special repository named exactly after your GitHub username.

✔ Once the repository is set up, you can edit the `README.md` to personalize your profile.

✔ Popular elements to include are:
   - GitHub Stats
   - Technical skills
   - Social media or contact links
     
✔✔✔🌱To make my contribution graph look more dynamic🌱, I used this awesome project:
   👉 [github-profile-3d-contrib by yoshi389111](https://github.com/yoshi389111/github-profile-3d-contrib)
   ---

### 🧩🌈🎨 How to Use github-profile-3d-contrib 🧩🌈🎨
🔧I had some issues when adding the workflow in the Actions tab, but I finally made it!🔧
Before writing my own YAML file, I had to generate a GitHub token and paste it into the file.

1️⃣ Create a special repository
Create a repository named exactly after your GitHub username (e.g., username/username).
(See the second part above if unsure.)

2️⃣ Generate a GitHub Token
Go to:
Settings > Developer settings > Personal access tokens > Tokens (classic) > Generate new token
Make sure to select the correct scopes, and set it to "no expiration" if you don’t want to renew it later.

3️⃣ Add the Token as a Secret
In your repository:
Go to Settings > Security > Secrets and variables > Actions
Click “New repository secret”, name it whatever you want (e.g., TOKEN), and paste the token.

4️⃣ Register a GitHub Action
In the Actions tab, click “New workflow”, then choose “set up a workflow yourself”.
Write your own YAML script (you can copy one from the github-profile-3d-contrib repo).
Don’t forget to replace the username and token name with your own.

5️⃣ Fix Permission Errors (if needed)
I had a permission error after setup.
I fixed it by changing settings here:
Settings > Actions > General
Uncheck the boxes like shown below:

<img width="606" height="377" alt="image" src="https://github.com/user-attachments/assets/b641b4e1-67d2-42b6-8585-6cb91cf09062" /> <img width="576" height="431" alt="image" src="https://github.com/user-attachments/assets/2f4e1d69-0cff-4e18-bc5e-0b246e6941fc" />

6️⃣ Add the SVG to Your README
used profile-night-rainbow.svg

###🎉 Tada! Everything works just fine now.
