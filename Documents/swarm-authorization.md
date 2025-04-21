Swarm Authorization
===================

In the following animation we have a set of human users as participants. All users are connected to other nodes via arrows ->. The nodes include the text inside the brackets as well, but the text inside parenthesis should be displayed as a note below or above that node. As you can tell, each user connects to two other nodes, a repository on Github and a swarm on Code Awareness. During the process some users get shifted from one swarm to the other, due to a rebase that was not published in the original swarm. The end result is that each user is moved to the new swarm as they come online and perform a new swarm authorization. Finally, the original swarm becomes empty and is deleted.
 I need you to give me an HTML/JS animation of this process. Please draw all nodes as rectangles.

Participants: Alice, Bob, Charlie, Diana, Eva, Fin, George
Start:
- Alice -> Github [SHA001] 
- Alice -> CodeAwareness [SHA001]
Next:
- Bob -> Github [SHA001]
- Bob -> CodeAwareness [SHA001]
- Charlie -> Github [SHA001]
- Charlie -> CodeAwareness [SHA001]
Next:
- Charlie -> Github [SHA002]
- Charlie -> CodeAwareness [SHA002]
- Diana -> Github [SHA002]
- Diana -> CodeAwareness [SHA002]
Next:
- Eva -> Github [SHA002]
Next:
- Eva -> (rebase outside CodeAwareness) Github [SHA003] (SHA002 disappears)
Next:
- Fin -> Github [SHA003]
- Fin -> (SHA002 not found) CodeAwareness.Fin [SHA003]
Next:
- Alice -> Github [SHA003]
- Alice -> CodeAwareness.Fin [SHA003] (rejoins the swarm)
Next:
- George -> Github [SHA003]
- George -> CodeAwareness.Fin [SHA003] (rejoins the swarm)
- Charlie -> Github [SHA003]
- Charlie -> CodeAwareness.Fin [SHA003] (rejoins the swarm)
Next:
- Bob -> Github [SHA003]
- Bob -> CodeAwareness.Fin [SHA003] (rejoins the swarm)
- Diana -> Github [SHA003]
- Diana -> CodeAwareness.Fin [SHA003] (rejoins the swarm)
Next:
- empty node CodeAwareness [SHA002] is deleted

