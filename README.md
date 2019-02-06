# Replication 1
Replicating models and figures in "Identifying Judicial Empathy: Does Having Daughters Cause Judges to Rule for Women’s Issues?" by Glynn and Sen.

NOTE TO ENXHI: Hi, most of the code in comments can and should be deleted.
 
Much of the replication code found here has been taken from the replication code supplied by the authors of the study at //link//. 

There have been alterations to this code, some small, some major. 

Changes:

convert variable names containing periods into containing underscores, i.e. "judge.means" becomes "judge_means"

table 1 was rewritten in order to more closesly match the style presented in the final paper.

table 5 (as labelled) was remodelled using logit regression using glm, instead of using the Zelig package.

Many comments were rewritten for more clarity/explanation.

Much extraneous code was omitted or modernized (for example, the user-defined function "cl"" was deleted).

