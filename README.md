# BernieOnIssues

This document describes things that are known to be broken, and how to add issue or sub-issue pages.

## To Do

	0. The issues are not appearing on the home page (works on @horserunning's local sever, must be a quick configuration issue.)**

	1. Only show a subset of issues on main page**

Each issue, either issue or subissue, corresponds to a single markdown file (e.g. education.markdown) in the "_issues" folder.

The goal is that only a subset of the issues appear on the home page (high level ones like Women, Children, and Family). The ones linked on the home page direct users to sub-issues that also have the example.com/issue/sub-issue-name URL path. This is an unfinished task since all issues appear on the home page currently.

	2. Styling**

Make colors of the site match BernieSanders.com colors.

	3. Display name of issue in Related Links

More elegant solution to display related issues. Right now, the issue page loops through a list in the issue page's front matter named "related_issues_pg" (e.g. [women, children]). It iterates through the names of the related markdown files and links to each one, and displays the link as its file name. We just want to display the name of the issue ("French Cuisine" instead of "french-cuisine")

	4. Add social media accounts and add e-mail to formspree form

	5. Add HTTPS

	6. Be able to easily add summaries of sub-issues in the front matter of the issue page (just filler text at the moment)


## Creating an ISSUE page
An issue page provides a summary of a high-level issue along with summaries for related sub-issues (e.g. Women includes summaries of Reproductive Health, Pay Equity)

1. Include a summary of the high level issue in the front matter with "summary: The quick brown fox jumps over the lazy dog"
2. Include the "sub_issues: [x, y, z]" to the frontmatter.
3. When the feature is added, include the summaries of sub-issues.
3. Include related links, if desired, with "related_issues_pg : [french-cuisine, mexican-food]" in the frontmatter.

## Creating a SUB-ISSUE page
A sub-issue page doesn't provide summaries of other issues. But they are basically a clean slate and the content is up to the researcher to decide. 

1. Type anything you want into the summary with "summary: anything you want"
2. Include related links, if desired, with "related_issues_pg : [french-cuisine, mexican-food]" in the frontmatter.