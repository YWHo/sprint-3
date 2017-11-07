# Sprint-3 3.1 Build Your Redesigned Site

## What happens to the layout when you resize the screen to less than 550 px. How do you think that works? 

Once I resize the screen to less than 550px, I observed that all the elements are collapsed into single column. The minor details are:
- Two phone images become a single image (because the one at the back is dissapeared)
- The phone image moved from the right, to the below of 'Stop coding' description
- 3 columns of 'Purchase Increase', 'Multi-device Users', and 'Sad Users' are collapsed into a single column, becomes 3 rows from top to bottom
- 2 columns of "I'M AN IMAGE" are collapsed into single column, becomes 2 rows from top to bottom.
- Some fonts have size increased or decreased.

This is possible because of the media queries. The specific line is at:
    @media (min-width: 550px) { ... }



