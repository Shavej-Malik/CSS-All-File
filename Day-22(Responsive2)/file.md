Absolute Units
 -> These are fixed. Do not relate aur depend upon other
px -> pixel -> 2px
pt -> point(1/72 inch) -> 4pt
cm -> centimeter -> 3cm
mm -> milimeter -> 2mm
in -> inches -> 6in

Realative Units
 -> These are fixed.Relate aur depend upon other
% -> Parent's element size
vw -> 1% viewport width
vh -> 1% viewport heigth
em -> it's own font size -> 1.5em {relative to the font size of its own or nearest ancestor}
      {use for Button padding relative to its own text size} 1em = 16px
rem -> root element font size(HTML) -> 2rem (use for margin,padding) 1rem = 16px
vmin -> 1% of smaller viewport dimension
vmax -> 1% of large viewport dimension
ch -> relative to the width of the "0"(Zero)
ex -> relative to thw x-heigth of the current font (rarely used)

100vw -> full viewport width
100vh -> full viewport height

clamp( Lowerlimit , value, UpperLimit) e.g clamp( 14px, 1vw, 18px)
{
    suppose we have clamp( 14px, 1vw, 18px). Then viewport's width is 1900px then 100vw = 1900px and 
    1vw = 19px.This range is going out of range (UpperLimit = 18px) then font size automatically set on 18px.
}