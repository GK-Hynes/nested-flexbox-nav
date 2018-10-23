# Nested flexbox nav

A nav using nested flexbox for vertical and horizontal centering. Built for Wes Bos' [Flexbox course](https://flexbox.io/).

See the page live [here](https://gk-hynes.github.io/nested-flexbox-nav/).

## Notes

Here you essentially want the `ul` to be set to `align-items: center` and `align-items: stretch`, which is sadly impossible. One solution is to nest flexbox containers withing flexbox containers.

Set the `li`s to also `display: flex` and the links will become flex items. Then set the links to `display: flex` and `align-items: center`, and this will target the span around the link content.

Before nesting:

![Screenshot of flexbox nav before nesting](https://res.cloudinary.com/gerhynes/image/upload/q_auto/v1540306756/Screenshot_2018-10-23_Nested_Flexbox_Nav_hc3ma7.png)

After nesting:

![Screenshot of flexbox nav after nesting](https://res.cloudinary.com/gerhynes/image/upload/q_auto/v1540306767/Screenshot_2018-10-23_Nested_Flexbox_Nav_1_qvppgs.png)
