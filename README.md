## Simplifying Network Automation with NetGru 

*... with Cisco DevNet's **Adrian Iliesiu***

### Network Port Self Service - *Maybe* it does not have to be the apocalypse

*Claudia de Luna*

Changing the vlan on a network interface is a common network operations activity and so few of our clients automate this activity!  I get it.

It sounds like a trivial problem but often it is not.

- Sometimes a user does not know what switch and port their device is connected to
- Sometimes the vlan they need is not on the switch (or is not configured correctly on the switch)

The systems and tooling to automate this workflow with sufficient guardrails and with full documentation have not been readily available in the past.  However, we are living in a different world now.

I've gotten into the habbit of asking: 
"Under what conditions would you let your users change the vlan on their network port?"

But 99% of the time the user would benefit from having this capability. 

- Their needs are met immediately and safely.  
- The IT organization shines.  

So many good things can come from offering a service like this and yet many organizations think this type of user self service can only lead to an apocalypse.

![astro1](images/astro1up.jpg)

---













port_selfservice_apocalypse

