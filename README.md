# An Analysis of Kickstarter Campaigns
Performing an analysis of global Kickstarter campaigns, to uncover trends in the successes and failures of these campaigns.

All data used is in this .xlsx file: [Kickstarter Data](/data-1-1-3-StarterBook.xlsx).

The data of the Kickstarter campaigns being used is limited to campaigns that were launched between **2014-05-05** and **2017-03-29**


## Initial Analysis

Using a stacked column visualization of the data, we get a broad look at the outcomes of Kickstarter campaigns sorted by **Parent Category.** and focussing on the **Outcome** of each.

![parent_category_outcomes](/chart_images/parent_category_outcomes.png)

It's very interesting to see **Theatre** taking the lead in volume of campaigns started. Also upon first look, it looks that **Music** seems to have the most successful of **Outcomes**.

---

Continuing with the stacked column visualization, let's take a more detailed look at the data sorted by **Subcategory** with each of their **Outcomes** visualized.

![subcategory_outcomes](/chart_images/subcategory_outcomes.png)

It seems that **Plays** take the lead in **Subcategory** volume of campaigns. If you look through this chart, you can see that a few **Subcategories** have seemingly 100% successful **Outcomes**. That data could be interesting to explore.

---

Does the **Launch Date** have any impact on the **Outcomes**? A line chart can help visualize this and find any patterns.

![outcomes_based_on_launch_date](/chart_images/outcomes_based_on_launch_date.png)

Campaigns launched in May look to exhibit the highest amount of **Successful Outcomes**

---

Using a box & whiskers visualization and focussing on **Goal Amounts** and **Pledge Amounts**, we get a clear picture of what could be seen as "safe" **Goal Amounts** for a campaign in it's respective area. Let's focus on looking at campaigns from **Great Britain**, under the **Musical** subcategory.

![gb_musicals_goals_pledges_box](/chart_images/gb_musicals_goals_pledges_box.png)

We can see that there is overlap in IQR of both **Goal Amount** and **Pledge Amount** which provides great feedback in this subcategory in **Great Britain**. A realistic goal could be set within that overlap, with historical evidence to show that there is a higher chance that the **Goal Amount** would be met by **Pledge Amounts**. Worth exploring more thoroughly.
