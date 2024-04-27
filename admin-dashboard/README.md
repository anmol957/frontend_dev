# Admin Dashboard

- You work at a startup that is building an interface for admins to see and delete users. The users will be provided via an API. Your job is to build out a working UI. See image below for reference.
- Note - this is for reference only. You don't need to build the exact same UI.
![image](https://github.com/anmol957/admin-dashboard/assets/61040390/1cb56a9b-9981-4f40-9655-1d13dc4c096b)

  ### These are the requirements :

1. Column titles must stand out from the entries.
2. There should be a search bar that can filter on any property.
3. You should be able to edit or delete rows in place.(There is no expectation of persistence. Edit and delete are expected to only happen in memory.)
4. You need to implement pagination: Each page contains 10 rows. Buttons at the bottom allow you to jump to any page including special buttons for first page, previous page, next page and last page. Pagination must update based on search/filtering. If there are 25 records for example that match a search query, then pagination buttons should only go till 3.
5. You should be able to select one or more rows. A selected row is highlighted with a grayish background color. Multiple selected rows can be deleted at once using the 'Delete Selected' button at the top right bin icon.
6. Checkbox on the top left is a shortcut to select or deselect all displayed rows. This should only apply to the ten rows displayed in the current page, and not all 50 rows.
7. Search box placeholder text should start with Search.
8. Search icon/button should have class as search-icon OR trigger search on ENTER.
9. Action element must be a button with a specific class name like edit, delete, save.
10. Navigation elements must be a div/button, and should have class name as first-page, previous-page, next-page and last-page and page numbers should be mentioned accordingly.
11. On clicking edit action in a row, it should be editable in the row itself.
12. feel free to use any libraries.
13. On executing, your application should be running successfully on deployed on vercel, netlify or any similar platform.

    **Note** :
The users are sorted by `id` field. There is no alphabetical sorting.

**Request Type :**
GET