# Generative-AI

Debugging

    from langchain.globals import set_debug
    
    set_debug(True)
    
    agent.run("Who directed the 2023 film Oppenheimer and what is their age? What is their age in days (assume 365 days per year)?")
    
    from langchain.globals import set_verbose
    
    set_verbose(True)
    
    agent.run("Who directed the 2023 film Oppenheimer and what is their age? What is their age in days (assume 365 days per year)?")

----
