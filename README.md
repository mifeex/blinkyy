# blinkyy
Auto image uploading

program Example1;
var x,y,z: real;
begin
write('Введите x, y, z: '); readln(x);
readln(y); readln(z);
if x+y+z > 1 then begin
x:= x/10; y:= y/10; z:= z/10;
end else
if (x<y) and (x<z) then x:= (y/2) + (z/2) else
if (y<x) and (y<z) then y:= (x/2) + (z/2) else
if(z<y) and (z<x) then z:= (x/2) + (y/2);
write(x,y,z); end.
