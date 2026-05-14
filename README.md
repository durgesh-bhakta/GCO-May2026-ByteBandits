## GCO-May2026

# Problem 1:
“Encrypted Coordinates”
Input - 72-101-108-108-111
Rule: - Convert ASCII codes to characters

# Problem 2:
You receive a stream of telemetry lines.
Each line may or may not be valid.
Rules:
A valid line contains exactly three integers
Integers may be separated by:
single space
multiple spaces
comma
comma + space
Any line with extra characters is invalid
 
Task
- Parse valid lines only
- For each valid line, compute the GCD of the three numbers
- Sum all GCDs

# Problem 3:
“Security Grid”
Given a 5x5 grid: 
1 1 0 0 1
0 1 1 0 0
0 0 1 0 1
1 0 0 1 1
0 0 1 0 0
Movement allowed: Up/down/left/right only
Find: Number of connected clusters

# Problem 4:
Objective
You are given a starting string and a target string. Your task is to determine:
The minimum number of steps required to transform the start string into the end string
The number of distinct shortest transformation paths

Input 
Plain Text
START: "AAAA"
END:   "BBBB"
 
Allowed Operations
At each step, you may:
Change exactly one character in the current string
Each character can only be changed to one of:
A, B, C
 
Constraints
A transformation is valid only if:
Exactly one character changes per step
The resulting string contains only the characters: A, B, C
The string must NOT contain the substring "CC"
You must not revisit the same string more than once in a path
 
Output
Return two values:
 
Plain Text
Length: <minimum number of steps>
Paths:  <number of distinct shortest paths>
 
Notes
You must consider all possible valid transformations
Only count paths that have the minimum possible length
If multiple shortest paths exist, count all of them
