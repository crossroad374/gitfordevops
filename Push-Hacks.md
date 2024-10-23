🚀 Git Push and Pull Made Easy! 🚀

Whether you're a seasoned developer or just getting started with Git, managing your code securely is essential. Today, I’m sharing two simple methods to push and pull code using Tokens and SSH keys in Git! 🔐


🚀 Two Methods to Push and Pull in Git

1️⃣ Method 1: Using Tokens (Classic)
Step 1: Generate a Token
Go to Settings in your GitHub or GitLab account.
Navigate to Developer Settings.
Select Tokens (Classic) and generate a new token with the necessary permissions.

Step 2: Change the Remote URL in Git
Open your terminal and check your current remote URL using:
git remote -v
This will display the current origin for your repository.
Now, update the remote URL with your generated token using this command:
git remote set-url origin https://<your-token>@github.com/username/repository.git
Replace <your-token> with the token you generated, and adjust username/repository to match your actual GitHub username and repository name.

Step 3: Push and Pull Your Changes
Once your remote URL is updated, you can push or pull changes as usual:

Push your changes:
git push origin main

Pull the latest changes:
git pull origin main


2️⃣ Method 2: Using SSH Key
Step 1: Generate SSH Key
Open your terminal and generate a new SSH key:
ssh-keygen 
This will generate a private and public key pair.

Step 2: Add SSH Key to GitHub/GitLab
Copy the public key by running:
cat ~/.ssh/id_rsa.pub
Go to Settings on GitHub or GitLab.
Navigate to SSH and GPG Keys and paste your public key there.

Step 3: Update the Remote URL in Git
Update your Git repository to use the SSH URL:
git remote set-url origin git@github.com:username/repository.git
Replace username/repository with your actual GitHub username and repository name.

Step 4: Push and Pull Using SSH
Now you can push and pull your changes securely without entering a password:

Push your changes:
git push origin main

Pull the latest changes:
git pull origin main


By following these methods, you can easily push and pull your code using either Tokens or SSH keys. Both are secure, but tokens are great for automation, while SSH is better for frequent development tasks.
