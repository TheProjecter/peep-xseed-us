Peep is a message protocol designed around the concept of a conversation. A Peep conversation is different from a typical sustained connection or session in that it has no definitive beginning or end, and the nodes involved may not remember the same parts of it.

Unlike message protocols such as SOAP, Peep resolves ambiguities through gradual clarification as opposed to a single monolithic specification shared between nodes, much like people do in a real conversation. This, along with Peep's minimum base specification of only five basic messages, make it uniquely suited for use in unreliable, low bandwidth networks and power constrained devices.

Peep treats the message issues of how it was sent, who sent it, and what it says, separately. This enhances security, as well allows these issues to be resolved on separate processors. It also closely mirrors how how a real letter is sent, open, and read, making it conceptually easier to understand and explain.

And since a Peep message is just a simple tree, it can take the form of any tree based format such as JSON or XML. The Peep API can even send DOM nodes as messages straight off the tree.