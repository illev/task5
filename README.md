Segments
Given: class Point, skeleton of class Segment.

Implement Segment methods:

Constructor, having start and end points as parameters.
Ensure that created segment exists and is not degenerative, i.e. start and end of the segment is not the same point.
double length()
Return length of the segment.
Point middle()
Return a middle point of the segment.
Point intersection(Segment another)
Return a point of intersection of the current segment and the given one.
Return null if there is no such point.
If segments are collinear, return null.
Note: Intersection point must be on both segments.

Segments
Given a class Point,
and a skeleton of class Segment,
implement Segment methods:

constructor with start and end points as parameters
Ensure that a created segment exists and is not degenerative which means that the start and the end of the segment is not the same point.

double length()
Return length of the segment.

Point middle()
Return a middle point of the segment.

Point intersection(Segment another)
Return a point of the intersection of the current segment and the given one.
Return null if there is no such point.
Return null if segments are collinear.
Please, note that intersection point must lay on both segments.

Hints:

Length reference
Midpoint reference
Intersection reference


Examples
You may use Main class to try your code.
There are some examples below.

Sample code:
...
double length = new Segment(new Point(0, 0), new Point(3, 4)).length();
System.out.println(length);

Output: 5

Sample code:
...
Segment first = new Segment(new Point(0, 0), new Point(4, 4));
Segment second = new Segment(new Point(2, 0), new Point(0, 2));
Point intersection = first.intersection(second);

System.out.println(intersection.getX());
System.out.println(intersection.getY());

Output:
1
1

Sample code:
...
Segment seqment = new Segment(new Point(2, 0), new Point(0, 2));
Point midpoint = segment.middle();

System.out.println(midpoint.getX());
System.out.println(midpoint.getY());

Output:
1
1

Sample code:
...
Segment first = new Segment(new Point(0, 0), new Point(4, 0));
Segment second = new Segment(new Point(2, 1), new Point(1, 2));
Point intersection = first.intersection(second);

System.out.println(intersection == null);

Output:
true

