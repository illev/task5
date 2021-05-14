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
