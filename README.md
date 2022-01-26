# BubbleChart
Draws a Bubble Chart from data 
circles in differenz sizes and colors adjacent to each other

Output:




Call:

        BubbleChart(data: $data, spacing: 0, startAngle: 180, clockwise: true)
            .font(.caption)

- data:     the chart data array, has to conform to [DataItem]  
- spacing:  Spacing between the circles  
- startAngle: angle in degrees 0..360° where the surrounding circles start (0° = horizontal to the right)
- clockwise: true or false, direction in which other circles are added

Font modifiers change the titles on the bubbles
