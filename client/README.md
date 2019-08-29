# Angular Print a page V1

This is an example of printing a page. It isn't very reusable and needs to be placed within its own module (that's what V2 will do).  Once V2 is done, I'll delete this repo.

## Links
This example is 
1. Based on mainly on [this article](https://medium.com/@Idan_Co/angular-print-service-290651c721f9)

Other helpful links.
1. [Greater control over page](https://www.w3.org/TR/1998/REC-CSS2-19980512/page.html)

## Topic: How to get rid of the URL at bottom of page
Basically it needs to be in styles.css
@media print {
  @page {
    size: auto;   /* auto is the initial value */
    margin: 0;  /* this affects the margin in the printer settings */
  }
}

Reference
- [The footer is too high](https://medium.com/@zerox/keep-that-damn-footer-at-the-bottom-c7a921cb9551)


