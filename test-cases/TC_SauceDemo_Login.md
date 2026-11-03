# Test cases: SauceDemo login and checkout

App: https://www.saucedemo.com

I'm still running these. Results get filled in as I go.

| ID | Scenario | Data | Expected | Actual | Status |
| -- | -------- | ---- | -------- | ------ | ------ |
| TC-SD-001 | Login with a valid account | standard_user / secret_sauce | Goes to the products page | | Not tested |
| TC-SD-002 | Wrong password | standard_user / wrong_pass | Error message, no login | | Not tested |
| TC-SD-003 | Empty username | (empty) / secret_sauce | Error: username is required | | Not tested |
| TC-SD-004 | Empty password | standard_user / (empty) | Error: password is required | | Not tested |
| TC-SD-005 | Locked account | locked_out_user / secret_sauce | Error: user is locked out | | Not tested |
| TC-SD-006 | Logout | logged in as standard_user | Back to the login page | | Not tested |
| TC-SD-007 | Add item to cart | standard_user | Cart badge shows 1 | | Not tested |
| TC-SD-008 | Finish a checkout | standard_user, valid info | Order confirmation page | | Not tested |
