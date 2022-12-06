<h3>Declaring Variables</h3>
Name [CONSTANT] datatype [NOT NULL] [:=|DEFAULT value|expression];<br>

***
<h4> Setting a Default Value </h4>
DECLARE <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;V_TEXT VARCHAR2 (50) NOT NULL DEFAULT 'HELLO'; <br>
BEGIN <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DBMS_OUTPUT.PUT_LINE(V_TEXT); <br>
END;<br>

***
<h4> Declaring a Value (other than the default)</h4>
DECLARE <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;V_TEXT VARCHAR2 (50) NOT NULL DEFAULT 'HELLO'; <br>
BEGIN <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;V_TEXT := 'PL/SQL'; <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DBMS_OUTPUT.PUT_LINE(V_TEXT); <br>
END; <br>

***
