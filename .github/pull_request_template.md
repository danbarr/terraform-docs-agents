### What
<!-- Explain what you changed and provide a list of changed page names. -->

### Why
<!-- Explain why this change is necessary and how it benefits users. -->

### Screenshots
<!-- Optional. Show additions to the sidebar or new formatting. -->

----------

### Merge Checklist
_If items do not apply to your changes, add (N/A) and mark them as complete._

#### Pull Request
- [ ] One or more labels describe the type of change (e.g. clarification) and associated product (e.g. HCP Terraform).
- [ ] Description links to related pull requests or issues, if any.

#### Content
- [ ] Redirects have been added for moved, renamed, or deleted pages. This requires a separate PR in the [`terraform-website` repository](https://github.com/hashicorp/terraform-website) `redirects.next.js` file.
- [ ] API documentation and the API Changelog have been updated. 
- [ ] Links to related content where appropriate (e.g., API endpoints, permissions, etc.).
- [ ] Pages with related content are updated and link to this content when appropriate.
- [ ] Sidebar navigation files have been updated for added, deleted, reordered, or renamed pages.
- [ ] New pages have metadata (page name and description) at the top.
- [ ] New images are 2048 px wide. They have HashiCorp standard annotation color (#F92672) and format (rectangle with rounded corners), blurred sensitive details (e.g. credentials, usernames, user icons), and descriptive alt text in the markdown for accessibility.
- [ ] New code blocks have the correct syntax and line breaks to eliminate horizontal scroll bars.
- [ ] UI elements (button names, page names, etc.) are bolded.
- [ ] The Vercel website preview successfully deployed.

#### Reviews
- [ ] I or someone else reviewed the content for technical accuracy.
- [ ] I or someone else reviewed the content for typos, punctuation, spelling, and grammar.
