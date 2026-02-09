# Migration Guide: Moving to Organization GitHub Pages

This guide explains how to migrate from a project page URL to an organization page URL.

## Current Setup
- **Current URL**: `https://vishalcodingninja.github.io/TheGrowthClub.Website/`
- **Repository**: `VishalCodingNinja/TheGrowthClub.Website`

## Target Setup
- **Target URL**: `https://TheGrowthClub.github.io`
- **Repository**: `TheGrowthClub/TheGrowthClub.github.io`

## Migration Steps

### Step 1: Create GitHub Organization
1. Go to GitHub and click the **+** icon in the top-right corner
2. Select **New organization**
3. Choose a plan (Free is fine for public repositories)
4. Enter organization name: **TheGrowthClub**
5. Complete the setup process

### Step 2: Transfer Repository Ownership
1. Navigate to the current repository: `https://github.com/VishalCodingNinja/TheGrowthClub.Website`
2. Go to **Settings** (top navigation)
3. Scroll down to the **Danger Zone** section
4. Click **Transfer ownership**
5. Enter the new owner: `TheGrowthClub`
6. Type the repository name to confirm
7. Click **I understand, transfer this repository**

### Step 3: Rename Repository
1. After transfer, navigate to: `https://github.com/TheGrowthClub/TheGrowthClub.Website`
2. Go to **Settings**
3. In the **Repository name** field, change it to: `TheGrowthClub.github.io`
4. Click **Rename**

**Important**: The repository name must exactly match the pattern `<organization>.github.io` for the organization page to work.

### Step 4: Configure GitHub Pages
1. In the repository settings, navigate to **Pages** (left sidebar)
2. Under **Source**, ensure:
   - Branch: `main` (or your default branch)
   - Folder: `/ (root)`
3. Click **Save**
4. Wait a few minutes for GitHub to build and deploy your site

### Step 5: Verify Deployment
1. Visit `https://TheGrowthClub.github.io` in your browser
2. Verify that the website loads correctly
3. Check all links and resources are working

## Why Organization Pages?

**Advantages:**
- Cleaner URL structure (no repository name in URL)
- Professional appearance for organization projects
- Root-level domain (easier to remember and share)
- Better for branding and SEO

**Considerations:**
- Each organization can only have ONE organization page (named `<org>.github.io`)
- Other repositories in the organization will be project pages (e.g., `TheGrowthClub.github.io/other-project`)

## Troubleshooting

### Site Not Loading
- Wait 5-10 minutes after enabling GitHub Pages
- Check that the repository name is exactly `TheGrowthClub.github.io`
- Verify GitHub Pages is enabled in repository settings
- Check the Pages tab for any error messages

### 404 Errors
- Ensure `index.html` is in the root directory
- Check that the branch selected in Pages settings has your code
- Verify file names are spelled correctly (case-sensitive)

### Custom Domain (Optional)
If you want to use a custom domain like `thegrowthclub.com`:
1. Add a `CNAME` file with your domain name
2. Configure DNS records with your domain provider
3. Add the custom domain in repository Settings → Pages

## Rollback Plan

If you need to revert:
1. Transfer repository back to personal account
2. Restore original repository name
3. Update GitHub Pages settings
4. URL will revert to: `https://vishalcodingninja.github.io/TheGrowthClub.Website/`

## Need Help?

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Creating an Organization](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/creating-a-new-organization-from-scratch)
- [Transferring a Repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/transferring-a-repository)
