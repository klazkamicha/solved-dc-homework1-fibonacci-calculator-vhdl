Download Link: https://assignmentchef.com/product/solved-dc-homework1-fibonacci-calculator-vhdl
<br>
Mathematically, we can define the <strong>n-th</strong> Fibonacci number as the sum of the <strong>(n-1)-th</strong> and <strong>(n-2)-th</strong>.

Given the following entity declaration for a Fibonacci Calculator, complete the architecture to provide a behavioral description for the Fibonacci calculator.

<strong><em>entity Fibonacci_Calculator is </em></strong>

<strong><em>      port (   clk           : in  std_logic;  </em></strong>

<strong><em>   data_in  : in  std_logic_vector (3 downto 0);      load_enable : in  std_logic;        data_out  : out std_logic_vector (9 downto 0)); end Fibonacci_Calculator; </em></strong>

<strong><em> </em></strong>

<strong><em>architecture behavioral of Fibonacci_Calculator is </em></strong>




(Note: <strong><u>Do not use algorithmic state machine</u></strong>)  You have to submit two files:

<ol>

 <li>A VHDL code to implement your Design.</li>

 <li>A testbench file to simulate and test your design.

  <ol>

   <li>You have to cover all the possible cases for the input data:</li>

   <li>For each case you have to:

    <ol>

     <li>Select a test value for data_in</li>

     <li>Activate the <strong>load_enable</strong> signal for at least one clock cycle.</li>

    </ol></li>

  </ol></li>

</ol>

<ul>

 <li>The Fibonacci number should be calculated at the rising edge of the input clock.</li>

</ul>