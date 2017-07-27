# wordpress-breadcrumb
This a Wordpress breadcrumb generator. 

Limits
1. The generator produces an ordered list.
2. It only works for a post with only one category. In case of multiple categories for a particular post, the generator picks the category that was first created in the Wordpress database. 
3. It does not detect a back-button navigation. For example, if you landed on a post coming from a Tag archive, the breadcrumb generator will show the category always. It does not display the referrer page. 
4. This is great for blogs and websites with neat architecture in terms of CATEGORY archiving. 
