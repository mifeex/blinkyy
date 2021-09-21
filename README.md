# blinkyy
Auto image uploading

program Example1; var k: integer;
var str: string; begin
write('Введите число:'); read(k);
if k=1 then str:= 'Плохо:(' else
if k = 2 then str:= 'неудовлетворительно' else
if k=3 then str:= 'удовлетворительно' else
if k=4 then str:= 'хорошо' else
if k=5 then str:= 'отлично'
else str:= 'ощибка(:'; write(str);
end.

