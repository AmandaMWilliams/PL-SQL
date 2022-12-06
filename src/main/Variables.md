<h3>Declaring Variables</h3><br>
<br>
Name [CONSTANT] datatype [NOT NULL] [:=|DEFAULT value|expression];<br>



<h4> Setting a default value </h4><br>
<br>
DECLARE <br>
    V_TEXT VARCHAR2 (50) NOT NULL DEFAULT 'HELLO'; <br>
BEGIN <br>
    DBMS_OUTPUT.PUT_LINE(V_TEXT); <br>
END; <br>

<h4> Declaring a value other than the default</h4><br>
<br>
DECLARE <br>
    V_TEXT VARCHAR2 (50) NOT NULL DEFAULT 'HELLO'; <br>
BEGIN <br>
    V_TEXT := 'PL/SQL'; <br>
    DBMS_OUTPUT.PUT_LINE(V_TEXT); <br>
END; <br>
