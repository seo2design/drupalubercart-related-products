# drupalubercart-related-products
A related products way useful for drupal+ubercart (drupal and commerce similar as it)

Drupal with ubercart module can build a simple and powerful online shopping ecommerce website, for many useage it is enough.
I use them (Drupal with ubercart module) for my oversea trade online businese more than 5 years.

Here is a better way to create a releated product in drupal+ubercart ecommerce website, this is a useful part to promotion your online sales,in other way, this is a better seo solution to promotion your keywords in google search.

I use a drupal module named:[Similar By Terms]. this modules also genarate a views block to show  releated products for current node( current product page), but this module  cause by i18n module or other else,[Similar By Terms] module will cause mysql too many many connections to make mysql work slowly, this is a bad for you whole website.

So, I try to find aother way to display a related product block without use [Similar By Terms].

Here is the solution:
use [Search Api+search views] to genaration a views block to show a related product block in current node ( current product page), this is a beeter way than use [Similar By Terms], use less server resource, NOT cause mysql server working slowly. and this block can show relate products more use more easy ways: You Can use [node title] or [body text] or [node terms] as a filter to show related content.

