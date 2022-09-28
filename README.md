# Fundamental-ICT-1.1

**Python:**

if temperature => 10:
  if current_day == weekday:
    if time => 6:00 and time =< 8:30:
      temperature = 20
    elif time => 17:30 and =< 22:00:
      temperature = 20
    else:
      repeat
  else:
    if time => 8:00 and time =< 23:00
      temperature = 22
else:
  boiler = on

**PsuedoCode:**

IF temperature => 10 THEN
  IF current_day == weekday THEN
    IF time =>  6:00 AND time =< 8:30 THEN
      SET temperature TO 20
    ELIF time => 17:30 and time =< 22:00 THEN
      SET temperature TO 20
  ELSE
    IF time => 8:00 AND time =< 23:00 THEN
      SET temperature TO 22
ELSE
    SET boiler TO on
END IF
