## ML causal testing

| [GitHub](https://github.com/INSPIRED-GMU/py-holmes-public)      |
| :---:        |

### Summary

Determining the root cause of a unit test failure usually takes up a significant portion of debugging time.  And when training machine learning models, finding the root cause can be especially time-consuming, as these models tend to be black boxes.  I'm currently working in the INSPIRED Lab of Dr. Brittany Johnson at George Mason University to develop a tool called py-holmes, which will present Python developers with a set of mutated versions of the original failing test, to streamline the debugging process.  I will be first author on an upcoming paper discussing this tool.

The public version of py-holmes is available via the button above.  Dr. Johnson previously developed a version of the tool for Java, called Holmes.  Below is an example of Holmes running in Eclipse IDE.

![CREDIT BRITTANY JOHNSON: Java Holmes example](/images/projects/ml_causal_testing/CREDIT_BRITTANY_JOHNSON_java_holmes_example.png)

### Skills gained
By conferring with faculty experts in various machine learning models and applications, I've broadened and deepened my knowledge of the ML landscape and how to implement ML models.

By using tools such as caches to read the user's project files in minimal time, I've been consolidating past experience in optimization.

I've become proficient with using Git Bash, which allows for easy updating of a GitHub repository.

I've learned how to read, parse, and modify abstract syntax trees and execution traces (such as the one excerpted below), which are necessary in extracting information from the original failing test and generating similar tests.

![Execution trace example](/images/projects/ml_causal_testing/execution_trace_example.png)
