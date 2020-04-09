# PayPlans

In this page you can create a plan based on your specifications.

This app uses [Stripe](https://stripe.com). You can check details about Stripe plans [here](https://stripe.com/docs/api/php#plans).

* **No. of people**  **field**: if you use 0 \(zero\) then you can create unlimited staff accounts or if you use any numerical value like 2 then you can create two staff account for your organization.
* **Trial field:** This field is used to assign the no. of trial days for the plan.
* **Card type**: This is to know whether your plan is of "With Card" or "Without Card". If you choose  "With Card" then it will ask you the card details while choosing this plan or if you choose "Without Card" then it won't ask you to enter the card details.
* **Plan visibility**: This is to enable the plan to be seen by normal user. If the plan is visible, All users can see it, and subscribe to it. If a plan is not visible, Only Admin users can see it. You can create special plans for specific purpose and assign only specific organizations to it or You can hide old plans which you don't want new user to access anymore.

**Note:**

You can create other values for "Currency" and "Interval" fields in OPTIONS page.

When updating any plan you cannot edit few of the parameters.

you can read it [here.](https://stripe.com/docs/api/php#update_plan)

