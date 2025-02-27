java c
Final Exam 
600.464/664   Artiﬁcial   Intelligence 
Spring   2020Informed Search                                                                                   10 points 
Consider   the   search   space   below,   where S is   the   start   node   and G satisﬁes   the   goal   test.    Arcs   are   labeled   with   the   cost   of   traversing   them   and   the   heuristic   cost   to   the   goal   is   reported   inside   nodes   (so   lower   scores   are   better).

1.    (10   points)   For   A*   search,   indicate   which   goal   state   is   reached   at   what   cost   and   list,   in   order,   all   the   states   popped   of   of   the   OPEN   list.   You   use   a   search   graph   to   show   your   work.   Do   not   expand   paths   that   revisit states   at   higher   cost. 
Note:   When   all   else   is   equal,   nodes   should   be   removed   from   OPEN   in alphabetical order.
Path to goal (cost): 
Search graph (indicate order of states popped of OPEN list with numbers):First Order Logic                                                                     15 points 
2.    (5   points)   Convert   the   following   sentences   into   ﬁrst-order   predicate   calculus   logic:
If a team wins a game, it is happy. 
If a team plays a game, is better than the opponent, and is in good form, it wins the game. 
The BlueJays play a game against the Tigers. 
The BlueJays are better than the Tigers. 
The BlueJays are in good form. 
3.    (5   points)   Convert   all   rules   to   Conjunctive   Normal   Form.    (CNF).   You   do   not   need   to   restate   rules   that   are   already   in   CNF.
4.    (5   points)   Carry   out   a   resolution   proof   of   the   statement The BlueJays are happy. Constraint Satisfaction                                                                                   15 points 
Consider   the   following   Mini   Sodoku   puzzle.
(numbers   are   assigned   values,   letters   are   names   for   cells)

Recall   the   rules   of   Sudoku:
•    Each   cell   is   assigned   a   number   (in   Mini   Sudoku,   the   numbers   are   1,   2,   and   3).
• No   row   can   have   the   same   number   twice.
• No   column   can   have   the   same   number   twice.
These   rules   can   be   speciﬁed   by   constraints.   You   do   not   need   to   formally   write   these   constraints   down.
5.    (8    points) Carry out   backtracking search.    Explore the search space in the alphabetic order of   the cell names,   and   assign   values   in   numerical   order   (i.e.,   ﬁrst   assign   1,   then   2,   then   3).   Draw   the   search   tree.   Stop   and   backtrack   at   leaves   where   constraints   allow   no   valid   variable   assignment.
6.    (7   points)   Now,   use   the   minimum   remaining   values   (MRV)   heuristic.    Fill   in   the   following   table.    Start   with   a   row   that   speciﬁes   the   remaining   possible   values   for   each   variable.   Then   commit   one   variable   to   a   value following   the   MRV   heuristic   (in   case   of ties   follow   alphabetical   order).
Planning                                                                                               15 points An   evil   robot   has   almost   completed   his   evil   plan   for   the   total   destruction   of   the   human   race.       He   has two   nasty   chemicals   called   A   and   B   which   are   currently   stored   in   containers   1   and   2   respectively.    All   he   has   to   do   now   is   mix   them   together   in   container   3.    His   designer,   an   equally   evil   computer   scientist,   has equipped   the   evil   robot with   a   propositional   planning   system   that   allows   him   to   reason   about   the   locations   of particular   things   and   about   moving   a   thing   from   one   place   to   another.
7.    (5   points)   Explain   how   this   problem   might   be   represented   within    a   proposit代 写600.464/664 Artificial Intelligence Spring 2020 Final ExamSQL
代做程序编程语言ional   planning   system.      Give   speciﬁc   examples   of the   way   in   which   the   start   state   and   goal   can   be   represented.
8.    (5   points)   Describe   in   detail   an   algorithm   that   can   be   used   to   ﬁnd   a   plan   using   this   form   of   representation.
9.    (2   points)   Give   a   speciﬁc   example   of   a   successor-state   axiom   using   the   representation   you   suggested.
10.    (3   points)   Explain   why   in   this   particular   planning   problem   it   might   be   necessary   to   include   one   or   more precondition   axioms   and   give   an   example   of   such   an   axiom   using   your   representation.Machine Learning                                                                                                15 points Consider   the   following   plot   of   data   points.
11.    (5   points)   Write down   the   formula   for   a   linear   classiﬁer   function   f   (x,   y)   → value where   positive output values correspond   to   the   sign + and   negative values correspond   to   the   sign – .   The   classiﬁer   should classify all   training   examples   corrrectly.
Now   consider   the   following   plot   of   data   points.

12.    (10   points)   Draw   a   neural   network   with   weight   values   that   classiﬁes   all   values   correctly.    You   may   use   the   following   activation   function.Reinforcement Learning                                                                                                 15 points Consider   the non-deterministic reinforcement   environment   drawn   below.    States   are   represented   by   circles,   and   actions   by   squares.      The   Probability   of   a   transitions   is   indicated   on   the   arc   from   actions   to   states. Immediate rewards   are   indicated   above   and   below   states.   Once   the   agent   reaches   the end state   the   current   episode   ends.

13.    (15   points)    Consider   two   possible   policies:    always   take    action X or   always   take   action Y.   For   each   policy,   compute   the   answers   to   the   following   questions.
(a)    What   paths   could   be   taken?
(b)    What   is   each   path’s   probability?
(c)    What   is   each   path’s   reward?
(d)    What   is   the   utility   of   each   state?Natural Language Processing                                                                                       15 points 
We   plan   to   build   a   database   of   which   persons   were   hired   at   which   company   from   the   corpus   of   news paper   articles.
The   database   table   looks   like   follows:

Consider   the   following   sentences
• Albert Altman was hired by Apple as a software developer. 
• Booking.com hired Brianna Bayer as an accountant. 
• Comcast hired as their new CEO Catherine Carter. 
14.    (3   points)   For   each   sentence,   write   a   string   pattern   matching   expression   that   extracts   the   relevant   informa-   tion   (use   any   pattern   matching   formalism   you   like).
15.    (3   points)   Annotate   each   sentence   with   dependency   relationships   with   appropriate   labels.
16.    (5   points)   Deﬁne   informally   a   pattern   over   dependency   structures   that   allows   you   to   extract   the   relevant information   from   all   the   example   sentences   for   the   database   table.
17.    (4   points)   Hiring    information   may   be   expressed   in   many   diferent   ways   in   natural   language.      Below   is   a   list   of   general   problems   in   natural   language   processing.    Give   an   example   sentence   that   contains   relevant hiring   information   for   out   database   that   demonstrates   why   each   of   these   problems   poses   a   challenge   for   our   simple   extraction   patterns.
•      Synonymy
•    Hypernymy
• Co-reference
• Semantic   inference


         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
