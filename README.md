# code_review_plugin_chatgpt
if you want gpt review your code based on gerrit or gitlab, our plug-in can help you to realize 
our code can successfull install in your dev gerrit env , and can help you review your code and give you feedback

we develop this tool from 0 to 1, we found that if you only  request to gpt, and gpt response to results to end user,
everytime it feedbacks diff results , not inconsistent, so we add vector database to store history , and nexttime user request 
the likely question , langchain use fuzz pattern to search likely results and tell you the solution the same time

we want our tool can expand more funcs and need you to fork our code to expand more funcs ,and give us any feedbacks or suggestions
we are happy to hear that

