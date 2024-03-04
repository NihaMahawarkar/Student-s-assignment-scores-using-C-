# Student-s-assignment-scores-using-C-
Basic calculation of the average of the student's assignment scores using C#
// initialize variables - graded assignments 
int currentAssignments = 5;

int sophia1 = 93;
int sophia2 = 87;
int sophia3 = 98;
int sophia4 = 95;
int sophia5 = 100;

int nicolas1 = 80;
int nicolas2 = 83;
int nicolas3 = 82;
int nicolas4 = 88;
int nicolas5 = 85;

int zahirah1 = 84;
int zahirah2 = 96;
int zahirah3 = 73;
int zahirah4 = 85;
int zahirah5 = 79;

int jeong1 = 90;
int jeong2 = 92;
int jeong3 = 98;
int jeong4 = 100;
int jeong5 = 97;

int sophiaSum = 0;
int nicolasSum = 0;
int zahirahSum = 0;
int jeongSum = 0;

int sophiaSum1 = sophia1 + sophia2 + sophia3 + sophia4 + sophia5;
int nicolasSum2 = nicolas1 + nicolas2 + nicolas3 + nicolas4 + nicolas5;
int zahirahSum3 = zahirah1 + zahirah2 + zahirah3 + zahirah4 + zahirah5;
int jeongSum4 = jeong1 + jeong2 + jeong3 + jeong4 + jeong5;

decimal sophiaScore;
decimal nicolasScore;
decimal zahirahScore;
decimal jeongScore;

decimal sophiaScore1 = (decimal)sophiaSum1 / currentAssignments; 
decimal nicolasScore1 =(decimal) nicolasSum2 / currentAssignments;
decimal zahirahScore1 = (decimal)zahirahSum3 / currentAssignments;
decimal jeongScore1 = (decimal) jeongSum4 / currentAssignments;

Console.WriteLine("Sophia: " + sophiaScore1 + " A");
Console.WriteLine("Nicolas: " + nicolasScore1 + " B");
Console.WriteLine("Zahirah: " + zahirahScore1 + " B");
Console.WriteLine("Jeong: " + jeongScore1 + " A");
