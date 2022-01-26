# BubbleChart
Draws a Bubble Chart from data 
circles in differenz sizes and colors adjacent to each other

Output:

![Alt text](/BubbleChart_example.png "Optional Title")


Call:

        BubbleChart(data: $data, spacing: 0, startAngle: 180, clockwise: true)
            .font(.caption)

- data:     the chart data array, has to conform to [DataItem]  
- spacing:  Spacing between the circles  
- startAngle: angle in degrees 0..360° where the surrounding circles start (0° = horizontal to the right)
- clockwise: true or false, direction in which other circles are added

Font modifiers change the titles on the bubbles

the data array has this form:

    // graph data
    @State private var data: [DataItem] = [
        DataItem(title: "chrome", size: 180, color: .green),
        DataItem(title: "firefox", size: 60, color: .red),
        DataItem(title: "safari", size: 90, color: .blue),
        DataItem(title: "edge", size: 30, color: .orange),
        DataItem(title: "ie", size: 50, color: .yellow),
        DataItem(title: "chrome", size: 120, color: .green),
        DataItem(title: "firefox", size: 60, color: .red),
        DataItem(title: "safari", size: 90, color: .blue),
        DataItem(title: "edge", size: 30, color: .orange),
        DataItem(title: "opera", size: 25, color: .mint)
    ]
