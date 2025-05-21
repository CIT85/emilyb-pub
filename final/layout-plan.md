# Homepage Layout Plan

## Header (Flexbox)
* Site title (top)
* nav (bottom; Flexbox row)

## Main
* Section 1: Featured Decades (Grid - 2 columns)
    - Figure (left)
    - Articles (right, 3 rows)
* Section 2: Beauty and Safety 
    - Paragraph
* Section 3: Modern Makeup (Grid - 2 columns)
    - Figure (left)
    - Paragraph (right)
    - Table (right)
* Section 4: Fashion Designers (Grid - 2 columns)
    - Figure (left)
    - List (right)

## Footer (Flexbox)
* AI tool (left)
* Site Information (center)
* Back to top (right)

# Standard I will follow
* Bootstrap

# My Responsiveness using Media Queries

## Header (Flexbox)
* xs: nav menu stacked vertically
* sm+: nav menu stacked horizontally

## Main
* Section 1: Featured Decades
    - xs-sm: single-column layout (image above, articles stacked below)
    - md: 2-column grid layout, image on left + 1 article on right
    - lg: 2-column grid layout, 2 articles on right
    - xl+: 2-column layout, 3 articles on right
* Section 3: Modern Makeup
    - xs-sm: single-column layout
    - md: 2-column grid layout; image on right, paragraph on left, table underneath
    - lg+: 2-column layout, article and table on right
* Section 4: Fashion Designers
    - xs-sm: single-column layout
    - md+: 2-column layout, list on right

## Footer (Flexbox)
* xs: content stacked vertically
* sm+: content stacked horizontally