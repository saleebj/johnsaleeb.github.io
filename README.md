# John Saleeb Personal Website

Welcome to the source repository for my personal website: **[johnsaleeb.co.us](https://johnsaleeb.co.us)**.
This site is built using **Jekyll** and hosted on **GitHub Pages**.

## 🌐 How to Connect Your Custom Domain (`johnsaleeb.co.us`)

To officially link the `johnsaleeb.co.us` domain to this GitHub Pages site, you must update the DNS settings with your domain registrar (e.g., Namecheap, GoDaddy, Google Domains/Squarespace, etc.).

### Step 1: Configure Apex Domain A-Records
Create four **A** records pointing your root domain (`@` or `johnsaleeb.co.us`) to GitHub's IP addresses:
* `185.199.108.153`
* `185.199.109.153`
* `185.199.110.153`
* `185.199.111.153`

### Step 2: Configure Subdomain CNAME Record (Optional)
If you want to use the `www` subdomain (i.e. `www.johnsaleeb.co.us` redirecting to your main site), create a **CNAME** record:
* **Host/Name**: `www`
* **Target/Value**: `saleebj.github.io`

### Step 3: Enforce HTTPS in GitHub Settings
Once your DNS changes propagate (usually takes 5–30 minutes):
1. Go to your repository settings on GitHub.
2. Select the **Pages** tab on the left sidebar.
3. Under **Custom domain**, ensure `johnsaleeb.co.us` is entered.
4. Check **Enforce HTTPS** to secure the connection.

---

## 🛠️ Local Development & Preview

If you want to edit and test your website locally on this computer:

1. Open your terminal in the workspace directory.
2. Build the site and host it locally:
   ```bash
   bundle exec jekyll serve
   ```
3. Open your browser and navigate to `http://localhost:4000`.
