# test215rdcls

# Problem to solve:
How could we verify the user interface and make sure the user interface work correctly?

# Importance:
The user interface (UI) is the space where interactions between humans and software occur. The goal of this interaction is to allow effective operation and control of the software from the human end, at the same time the software simultaneously feeds back information that useful to the users.
The goal user interface is to produce a user interface which makes it easy, efficient, and enjoyable (user-friendly) to operate a software in the way which produces the desired result. This generally means that the operator needs to provide minimal input to achieve the desired output, and also that the software minimizes undesired outputs to the human. As the result, the quality of user interface is an important part to the quality of the entire software. Also, the user interface has the most impact on user.

# Current state:
What is a good UI? The HCI field always focus on defining a user-friendly UI and provides a set of principle to guide the UI design work. Also, checklist is devleoped for UI test.  However, the problem that whether the UI provides the functions that exactly match with the requirements receives less attention. Function tests tend to focus on backend. For the front engineers, when they finish the development of the user interface, they tend to check whether it works by clicking the user interface. For the QA team, the test on user interface is not a easy work. One of the reason is that the test on UI is not easy to track. Also, it should develop kinds of scenarios based on the requirements and design a sequence of user action to perform the scenarios. Also, at the same, it needs to supervise the result of test. The test on user interface is performed slightly. 


# Proposed solution:
A behavior-drive UI test framework tool may help the Ui testing process. The test scripts are developed based on the scenarios documented as features of this software. The test scripts run automatically and the terminal shows which scenario is test-passed and which failed.

A plugin will be developed and used as the extension of Selenium. The plugin will import the behavior-drive model into Selenium and makes it test based on scenarios. 

# Research question:
How to improve the UI test process?

# Evaluation plan:
Test GoodERP on Linux environment using the framwork we developed.


