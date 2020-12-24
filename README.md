Defining Methods


Here is an example of a typical method declaration:

public double calculateAnswer(double wingSpan, int numberOfEngines,
                              double length, double grossTons) {
    //do the calculation here
}
The only required elements of a method declaration are the method's return type, name, a pair of parentheses, (), and a body between braces, {}.

More generally, method declarations have six components, in order:

Modifiers—such as public, private, and others you will learn about later.
The return type—the data type of the value returned by the method, or void if the method does not return a value.
The method name—the rules for field names apply to method names as well, but the convention is a little different.
The parameter list in parenthesis—a comma-delimited list of input parameters, preceded by their data types, enclosed by parentheses, (). If there are no parameters, you must use empty parentheses.
An exception list—to be discussed later.
The method body, enclosed between braces—the method's code, including the declaration of local variables, goes here.
