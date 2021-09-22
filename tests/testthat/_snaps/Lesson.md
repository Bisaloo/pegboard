# Lessons can be validated [plain]

    Code
      vhead <- frg$validate_headings()
    Message <cliMessage>
      ! All headings must have unique IDs.
      -- Heading structure -----------------------------------------------------------
    Output
      # Episode: "For Loops" 
      +-## A for loop executes commands once for each value in a collection. 
      +-## A for loop is made up of a collection, a loop variable, and a body. 
      +-## The first line of the for loop must end with a colon, and the body must be 
      +-## Loop variables can be called anything. 
      +-## The body of a loop can contain many statements. 
      +-## Use range to iterate over a sequence of numbers. 
      +-## The Accumulator pattern turns many values into one. 
      +-## Classifying Errors 
      +-## Solution  (duplicated)
      +-## Tracing Execution 
      +-## Solution  (duplicated)
      +-## Reversing a String 
      +-## Solution  (duplicated)
      +-## Practice Accumulating 
      +-## Solution  (duplicated)
      +-## Solution  (duplicated)
      +-## Solution  (duplicated)
      +-## Solution  (duplicated)
      +-## Cumulative Sum 
      +-## Solution  (duplicated)
      +-## Identifying Variable Name Errors 
      +-## Solution  (duplicated)
      +-## Identifying Item Errors 
      \-## Solution  (duplicated)
    Message <cliMessage>
      --------------------------------------------------------------------------------
      ! All headings must have unique IDs.
      -- Heading structure -----------------------------------------------------------
    Output
      # Episode: "Looping Over Data Sets" 
      +-## Use a for loop to process files given a list of their names. 
      +-## Use glob.glob to find sets of files whose names match a pattern. 
      +-## Use glob and for to process batches of files. 
      +-## Determining Matches 
      +-## Solution  (duplicated)
      +-## Minimum File Size 
      +-## Solution  (duplicated)
      +-## Comparing Data 
      \-## Solution  (duplicated)
        \-### ZNK test links and images 
    Message <cliMessage>
      --------------------------------------------------------------------------------

---

    Code
      vlink <- frg$validate_links()
    Message <cliMessage>
      ! These files do not exist in the lesson:
      ::warning file=14-looping-data-sets.md,line=191::../no-workie.svg [missing file]
      ::warning file=14-looping-data-sets.md,line=197::../no-workie.svg [missing file]
      ! Images need alt-text:
      <https://webaim.org/techniques/hypertext/link_text#alt_link>
      ::warning file=14-looping-data-sets.md,line=195::https://carpentries.org/assets/img/TheCarpentries.svg [missing alt text]
      ::warning file=14-looping-data-sets.md,line=197::../no-workie.svg [missing alt text]

# Lessons can be validated [ansi]

    Code
      vhead <- frg$validate_headings()
    Message <cliMessage>
      [33m![39m All headings must have unique IDs.
      -- Heading structure -----------------------------------------------------------
    Output
      # Episode: "For Loops" 
      +-## A for loop executes commands once for each value in a collection. 
      +-## A for loop is made up of a collection, a loop variable, and a body. 
      +-## The first line of the for loop must end with a colon, and the body must be 
      +-## Loop variables can be called anything. 
      +-## The body of a loop can contain many statements. 
      +-## Use range to iterate over a sequence of numbers. 
      +-## The Accumulator pattern turns many values into one. 
      +-## Classifying Errors 
      +-## Solution  [7m(duplicated)[27m
      +-## Tracing Execution 
      +-## Solution  [7m(duplicated)[27m
      +-## Reversing a String 
      +-## Solution  [7m(duplicated)[27m
      +-## Practice Accumulating 
      +-## Solution  [7m(duplicated)[27m
      +-## Solution  [7m(duplicated)[27m
      +-## Solution  [7m(duplicated)[27m
      +-## Solution  [7m(duplicated)[27m
      +-## Cumulative Sum 
      +-## Solution  [7m(duplicated)[27m
      +-## Identifying Variable Name Errors 
      +-## Solution  [7m(duplicated)[27m
      +-## Identifying Item Errors 
      \-## Solution  [7m(duplicated)[27m
    Message <cliMessage>
      --------------------------------------------------------------------------------
      [33m![39m All headings must have unique IDs.
      -- Heading structure -----------------------------------------------------------
    Output
      # Episode: "Looping Over Data Sets" 
      +-## Use a for loop to process files given a list of their names. 
      +-## Use glob.glob to find sets of files whose names match a pattern. 
      +-## Use glob and for to process batches of files. 
      +-## Determining Matches 
      +-## Solution  [7m(duplicated)[27m
      +-## Minimum File Size 
      +-## Solution  [7m(duplicated)[27m
      +-## Comparing Data 
      \-## Solution  [7m(duplicated)[27m
        \-### ZNK test links and images 
    Message <cliMessage>
      --------------------------------------------------------------------------------

---

    Code
      vlink <- frg$validate_links()
    Message <cliMessage>
      [33m![39m These files do not exist in the lesson:
      ::warning file=14-looping-data-sets.md,line=191::../no-workie.svg [missing file]
      ::warning file=14-looping-data-sets.md,line=197::../no-workie.svg [missing file]
      [33m![39m Images need alt-text:
      <https://webaim.org/techniques/hypertext/link_text#alt_link>
      ::warning file=14-looping-data-sets.md,line=195::https://carpentries.org/assets/img/TheCarpentries.svg [missing alt text]
      ::warning file=14-looping-data-sets.md,line=197::../no-workie.svg [missing alt text]

# Lessons can be validated [unicode]

    Code
      vhead <- frg$validate_headings()
    Message <cliMessage>
      ! All headings must have unique IDs.
      ── Heading structure ───────────────────────────────────────────────────────────
    Output
      # Episode: "For Loops" 
      ├─## A for loop executes commands once for each value in a collection. 
      ├─## A for loop is made up of a collection, a loop variable, and a body. 
      ├─## The first line of the for loop must end with a colon, and the body must be 
      ├─## Loop variables can be called anything. 
      ├─## The body of a loop can contain many statements. 
      ├─## Use range to iterate over a sequence of numbers. 
      ├─## The Accumulator pattern turns many values into one. 
      ├─## Classifying Errors 
      ├─## Solution  (duplicated)
      ├─## Tracing Execution 
      ├─## Solution  (duplicated)
      ├─## Reversing a String 
      ├─## Solution  (duplicated)
      ├─## Practice Accumulating 
      ├─## Solution  (duplicated)
      ├─## Solution  (duplicated)
      ├─## Solution  (duplicated)
      ├─## Solution  (duplicated)
      ├─## Cumulative Sum 
      ├─## Solution  (duplicated)
      ├─## Identifying Variable Name Errors 
      ├─## Solution  (duplicated)
      ├─## Identifying Item Errors 
      └─## Solution  (duplicated)
    Message <cliMessage>
      ────────────────────────────────────────────────────────────────────────────────
      ! All headings must have unique IDs.
      ── Heading structure ───────────────────────────────────────────────────────────
    Output
      # Episode: "Looping Over Data Sets" 
      ├─## Use a for loop to process files given a list of their names. 
      ├─## Use glob.glob to find sets of files whose names match a pattern. 
      ├─## Use glob and for to process batches of files. 
      ├─## Determining Matches 
      ├─## Solution  (duplicated)
      ├─## Minimum File Size 
      ├─## Solution  (duplicated)
      ├─## Comparing Data 
      └─## Solution  (duplicated)
        └─### ZNK test links and images 
    Message <cliMessage>
      ────────────────────────────────────────────────────────────────────────────────

---

    Code
      vlink <- frg$validate_links()
    Message <cliMessage>
      ! These files do not exist in the lesson:
      ::warning file=14-looping-data-sets.md,line=191::../no-workie.svg [missing file]
      ::warning file=14-looping-data-sets.md,line=197::../no-workie.svg [missing file]
      ! Images need alt-text:
      <https://webaim.org/techniques/hypertext/link_text#alt_link>
      ::warning file=14-looping-data-sets.md,line=195::https://carpentries.org/assets/img/TheCarpentries.svg [missing alt text]
      ::warning file=14-looping-data-sets.md,line=197::../no-workie.svg [missing alt text]

# Lessons can be validated [fancy]

    Code
      vhead <- frg$validate_headings()
    Message <cliMessage>
      [33m![39m All headings must have unique IDs.
      ── Heading structure ───────────────────────────────────────────────────────────
    Output
      # Episode: "For Loops" 
      ├─## A for loop executes commands once for each value in a collection. 
      ├─## A for loop is made up of a collection, a loop variable, and a body. 
      ├─## The first line of the for loop must end with a colon, and the body must be 
      ├─## Loop variables can be called anything. 
      ├─## The body of a loop can contain many statements. 
      ├─## Use range to iterate over a sequence of numbers. 
      ├─## The Accumulator pattern turns many values into one. 
      ├─## Classifying Errors 
      ├─## Solution  [7m(duplicated)[27m
      ├─## Tracing Execution 
      ├─## Solution  [7m(duplicated)[27m
      ├─## Reversing a String 
      ├─## Solution  [7m(duplicated)[27m
      ├─## Practice Accumulating 
      ├─## Solution  [7m(duplicated)[27m
      ├─## Solution  [7m(duplicated)[27m
      ├─## Solution  [7m(duplicated)[27m
      ├─## Solution  [7m(duplicated)[27m
      ├─## Cumulative Sum 
      ├─## Solution  [7m(duplicated)[27m
      ├─## Identifying Variable Name Errors 
      ├─## Solution  [7m(duplicated)[27m
      ├─## Identifying Item Errors 
      └─## Solution  [7m(duplicated)[27m
    Message <cliMessage>
      ────────────────────────────────────────────────────────────────────────────────
      [33m![39m All headings must have unique IDs.
      ── Heading structure ───────────────────────────────────────────────────────────
    Output
      # Episode: "Looping Over Data Sets" 
      ├─## Use a for loop to process files given a list of their names. 
      ├─## Use glob.glob to find sets of files whose names match a pattern. 
      ├─## Use glob and for to process batches of files. 
      ├─## Determining Matches 
      ├─## Solution  [7m(duplicated)[27m
      ├─## Minimum File Size 
      ├─## Solution  [7m(duplicated)[27m
      ├─## Comparing Data 
      └─## Solution  [7m(duplicated)[27m
        └─### ZNK test links and images 
    Message <cliMessage>
      ────────────────────────────────────────────────────────────────────────────────

---

    Code
      vlink <- frg$validate_links()
    Message <cliMessage>
      [33m![39m These files do not exist in the lesson:
      ::warning file=14-looping-data-sets.md,line=191::../no-workie.svg [missing file]
      ::warning file=14-looping-data-sets.md,line=197::../no-workie.svg [missing file]
      [33m![39m Images need alt-text:
      <https://webaim.org/techniques/hypertext/link_text#alt_link>
      ::warning file=14-looping-data-sets.md,line=195::https://carpentries.org/assets/img/TheCarpentries.svg [missing alt text]
      ::warning file=14-looping-data-sets.md,line=197::../no-workie.svg [missing alt text]

