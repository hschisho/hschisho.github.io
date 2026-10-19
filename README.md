# pizzaCRM (test site) setup instructions:
https://docs.google.com/document/d/1Va1adtrh_kF_DGzE7dQH2Uaw2gcy9PwAyG3wl3nMwPk/edit?tab=t.0#heading=h.lxbs1vph2c0v

## Site navigation

Navigating from one page to another only works if you start at the home page and use the navigational menu buttons on the left. You cannot go directly to any subpages (for example **Accounts**, **Contacts**, **Opportunities**) via the direct URL—you will get a **404** error. This is a limitation of how this test site is built.

## Building Pendo guides on this site

Because of the routing limitation above, keep the following in mind when using the Visual Design Studio and multi-page guides.

### Launching the Designer

When launching Designer to build or edit a guide, launch the Designer over the **homepage**. Then use **Navigate** within the Designer so that you can get to the desired subpage.

### Multi-page guides

If you are building a guide that takes the user across multiple pages in the test site, **do not** use the **URL Link** button action. Instead, use a tooltip and **advance on element click** so that the user is directed to click on the navigational menu within the product.

Prefer a video? Check out the first guide option discussed in this Academy course: [Creating multi-page walkthrough guides](https://academy.pendo.io/creating-multi-page-walkthrough-guides).
