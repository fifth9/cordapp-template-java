# Update Java
Installed the latest JDK

# Build and Run Nodes
`$ ./gradlew clean deployNodes`

`$ build/nodes/runnodes`

# Interacting via the node consoles
There are some errors in the tutorial documentation.  Make sure that you run the following:

From PartyA
`start IOUFlow iouValue: 99, otherParty: "O=PartyB,L=New York,C=US"`

From PartyA or PartyB
`run vaultQuery contractStateType: com.template.states.IOUState`