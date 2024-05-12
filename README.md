DECLARE  	x int; BEGIN 
	 	x := 15; 
	 	if mod(x,2) = 0 then 
	 	 	dbms_output.put_line('Even Number'); 
	 	else 
	 	 	dbms_output.put_line('Odd Number'); 
	 	end if; 
END; / 
Output: 
Odd Number 
