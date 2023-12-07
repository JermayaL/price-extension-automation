**README**
<ol>
  <li>Insert the script into a Single account.</li>
    <li>It only works if a product group has a minimum of 3 products.</li>
  <li>Copy your Google Merchant Centre ID in row 2.</li>
  <li>Copy the spreadsheet template</li>
  <li>Adjust the country code and days of historical data. And change PriceType if needed.</li>
  <li>Activate the Advanced API “Shopping content”.</li>
  <li>Run the script. At the log you will see the product types. These could not be linked
based on the breadcrumbs. Add them once manually as a label per ad group.</li>
    <li>For instance: label an ad group: Laptops to an ad group about laptops. Now it
will set-up the top performers as a price extension. 5. Run it every hour or every day</li>
</ol>

**How it works**
The script looks to see if a productTitle is longer than 25 characters. If it is. Then it leaves column C from the sheet blank. If the productTitle is shorter than 25 characters, then it adds it in column C as a rewrite title.

For products that are > 25 characters, you must complete column C yourself once. The title from GMC is shown in column B. Along with the product_ID. You have to complete this once.

This also applies to the description. But for the description, you can use the retailer's USPs, for example (In stock, Free shipping, etc).

Once you have completed columns C and D, you can run the script again. I would have the script run daily, for example, for price and stock updates. It does not overwrite columns C and D. You can update these columns at any time.

**V3 is coming. This is expected to be live within 2 weeks. In it, I'm going to include the product feed to add descriptions automatically. And if possible, then other variables in the title as well. For example, that it should grab the headline from another field, such as short_title.**
