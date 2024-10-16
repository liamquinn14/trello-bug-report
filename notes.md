# Exploratory Testing: Trello Clone

## Notes
- Image background makes description text hard to read
- 'Tour', 'Pricing' and 'Learn' not clickable
- No login title in Login screen. Even after redirected after sign up.
- No back button in Login screen. Have to use browser
- Not a 'username' or 'password' heading for input boxes. Do screen readers read that? This applies to Login and Signup. Only use placeholders. No explanation for the choose file in signup.
- No back button in Signup screen
- Sign up button is unclickable while password length is too short. However, there is no text to tell the user exactly why it's unclickable. User needs to infer that it's because of password length. Exacerbated when applied to visually impaired users with screen readers.
- Password field in signup seemingly has no max length
- Menu in top-right not clickable
- UI completely broken on mobile - 90% of users use mobile
- Add project button sometimes not clickable. After exitting it.
- Create project: No max length on any input fields
- Settings and Business class not clickable on team profile
- When creating a board, due to image backgrounds, the board title placeholder doesn't have enough contrast
- Cannot access create board with tab navigation
- Typing in enter when naming board cancels creation of board. You would expect the opposite
- Board screen looks much better on mobile compared to the dashboard
- Can't add list with tab navigation
- No obvious way to delete lists
- When adding 3 lists, the add list button is hidden and requires scrolling. Even worse on mobile
- Titles of lists don't have max length. Breaks styling
- Reordering lists completely breaks the app
- Renaming boards doesn't work either

## Summary
- All 4 features do not work
- Lots of areas not clickable, including templates
- Not enough headings to explain to the user what to do
- Nice desktop UI, especially navbar in dashboard
- UI breaks on mobile in some places
- No back buttons in sign up and login
- Accessibility and tab navigation problems
- No max length on input fields
- Board screen easy to break with long-named lists, or too many lists

## Bugs

## Issues
- Unsplash API key not working until halfway through