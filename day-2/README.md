# CSS em and rem

## Key Points

- Font size compounds in em. 

- Example: if parent body font size is 16px then its child define with 2 em will be 2 * 16px and its child have font size of 2 em will be 2 * 16 * 2px;

- rem always looks at root element html { }.

- em looks at parent element.

- margin, padding and other properties when define with em look at the same element font size. rem always look at root.

- Suggestion for em: 
    - em works really well with button
    - example when we use padding with em and decrease the font size the padding and other stuff become small too.

- When you want spacing consitent use rem.

- Using rem and em make it easy to scale and use media queries.
