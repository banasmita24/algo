## Project Structure

.
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug.yml    
│   │   ├── config.yml
│   │   ├── custom.yml
│   │   ├── documentation.yml      
│   │   ├── feature.yml
│   │   └── idea.yml         
│   ├── workflows/
│   │   ├── add-contributor.yml    
│   │   ├── autolabel.yml
│   │   ├── codeql.yml   
│   │   ├── dependency-review.yml   
│   │   ├── deploy.yml            
│   │   ├── issue_close_open.yml                 
│   │   ├── lighthouse-report.yml  
│   │   ├── lighthouserc.json
│   │   ├── pr_merge.yaml
│   │   ├── pr_raise.yml
│   │   ├── pr_validation.yml
│   │   ├── release-drafter.yml
│   │   ├── release.yml
│   │   ├── stale.yml
│   │   └── test-deploy.yml   
│   ├── CODEOWNERS
│   ├── PULL_REQUEST_TEMPLATE.md
│   └── release-drafter.yml
│
├── admin/scripts
│   ├── formatLighthouseReport.js
│   └── package.json
│
├── blog/
│   ├── 20-most-important-coding-pattern.md
│   ├── Common-Recursion-Patterns.md
│   ├── Exploring-Graph-Algorithms.md
│   ├── Getting-started-with-array-data-structure.md
│   ├── Kadanes-algorithm.md
│   ├── Recursion-vs-Iteration.md
│   ├── Understanding-Graph-Representation.md
│   ├── a-very-useful-data-structure-string.md
│   ├── authors.yml
│   ├── balancing-speed-and-memory-A-Guide-to-Time-and-Space-Complexity.md
│   ├── language-matters-your-path-to-dsa-success-starts-here.md
│   ├── mastering-recursion.md
│   ├── omega-notation-the-key-to-understanding-algorithm-efficiency.md
│   ├── optimizing-recursive-functions.md
│   ├── practical-applications-of-recursion.md
│   ├── understanding-big-o-notation.md
│   └── understanding-time-space-complexity.md
│
├── docs/
│   ├── DSA-Problem-Solution/
│   │   ├── Add_two_number_as_LL.md
│   │   ├── Cousins in Binary Tree.md
│   │   ├── Delete middle node.md
│   │   ├── Delete_occurences_of_key.md
│   │   ├── Loop in linked list.md
│   │   ├── Merge Two Sorted Arrays.md
│   │   ├── Palindrome-number.md
│   │   ├── Segregate even and odd nodes in LinkedList.md
│   │   ├── Symmetric Tree.md
│   │   ├── flattening-a-linked-list.md
│   │   ├── house-robber.md
│   │   ├── longest_substring_without_repeated_characters.md
│   │   ├── merge_intervals.md
│   │   ├── odd-even-linked-list.md
│   │   ├── palindrome_linked_list.md
│   │   ├── partition_equal_subset_sum.md
│   │   ├── removing-stars-from-string.md
│   │   ├── reverse-bits.md
│   │   ├── reverse-linked-list.md
│   │   └── two_sum.md
│   ├── Divide and Conquer/
│   │   └── Maximum-minimum.md
│   ├── Hashing/
│   │   ├── CollisionHandling.md
│   │   ├── OperationInsertion.md
│   │   ├── OperationSearch.md
│   │   ├── OperationUpdate.md
│   │   ├── Tigerhashing.md
│   │   ├── _category_.json
│   │   ├── deletion-in-hash-table.md
│   │   ├── hashsets.md
│   │   ├── imp-of-hashing.md
│   │   └── what-is-hashing.md
│   ├── Number Theory/
│   │   ├── GCD.md
│   │   ├── LCM.md
│   │   └── sieve-of-eratosthenes.md
│   ├── Object Oriented Programming/
│   │   ├── 4-pillars-of-oops.md
│   │   ├── ApplicationofOOPS.md
│   │   ├── _category_.json
│   │   ├── car.png
│   │   ├── classes-and-objects.md
│   │   ├── constructors-destructors.md
│   │   ├── interfaces-vs-abstract-classes.md
│   │   ├── intro-to-oops.md
│   │   ├── intro.png
│   │   ├── real-world-examples.md
│   │   └── typesOfInheritance.md
│   ├── Queue/
│   │   ├── Blocked-queue.png
│   │   ├── Circular-queue.png
│   │   ├── Priority-queue.png
│   │   ├── Problem-Practice.md
│   │   ├── _category_.json
│   │   ├── blocked-queue.md
│   │   ├── check-palindrome-using-dequeue.md
│   │   ├── circular-queue.md
│   │   ├── concurrent-queue.md
│   │   ├── double-ended-queue.md
│   │   ├── doubleendedqueue.png
│   │   ├── priority-queue.md
│   │   └── priority_queue_questions.md
│   ├── Recursion/
│   │   ├── Ackerman.md
│   │   ├── Count-all-subsequences-with-sum-K.md
│   │   ├── GrayCodeGeneration.md
│   │   ├── Josephus-Queries.md
│   │   ├── Knight's_Tour_Problem.md
│   │   ├── Letter-Combinations-of-a-Phone-number.md
│   │   ├── N Queen 2.png
│   │   ├── N Qween 1.png
│   │   ├── Sodoko.md
│   │   ├── TowersOfHanoi.md
│   │   ├── VoseAlias.md
│   │   ├── WaterJug.md
│   │   ├── _category_.json
│   │   ├── catalannumber.md
│   │   ├── generate-parantheses.md
│   │   ├── josephus.md
│   │   ├── look-and-say.md
│   │   ├── n-Queen.md
│   │   ├── recursion.md
│   │   └── ulamsequence.md
│   ├── Segment-Trees/
│   │   ├── Dynamic Segment Trees.md
│   │   ├── Practice Problem.md
│   │   ├── Segment Trees Introduction.md
│   │   └── Segment-Tree-img.png
│   ├── Sliding-Window/
│   │   ├── IntroductionToSlidingWindow.jpg
│   │   ├── Problem-Practice.md
│   │   ├── _category_.json
│   │   ├── introduction-to-sliding-window.md
│   │   ├── longest-repeating-character-replacement.md
│   │   ├── longest-substring-with-K-different-characters.md
│   │   ├── maximum-sum-subarray-size-K.md
│   │   └── minimize-maximum-of-two-arrays.md
│   ├── Stack/
│   │   ├── Conversion.md
│   │   ├── Evaluation.md
│   │   ├── Introduction_to_Stack.png
│   │   ├── Min-Stack.md
│   │   ├── MonotonicStack.md
│   │   ├── Problem-Practice.md
│   │   ├── Stack-permutation.md
│   │   ├── _category_.json
│   │   ├── introduction-to-stack.md
│   │   └── stack.md
│   ├── Standard Template Library/
│   │   ├── STL-algorithms.md
│   │   ├── STL-containers.md
│   │   ├── STL-iterators.md
│   │   └── STL-theory.md
│   ├── Strings/
│   │   └── Problem-Practice.md
│   ├── Tarjan's Algorithm/
│   │   ├── Tarjan.md
│   │   └── algorithm.png
│   ├── Task Scheduling/
│   │   ├── Task-schedule.md
│   │   └── _category_.json
│   ├── Trees/
│   │   ├── B-Trees.md
│   │   ├── Expression-tree.md
│   │   ├── Heap-tree.md
│   │   ├── Practice Problems.md
│   │   ├── Trees Practice Problems.md
│   │   ├── Types of Trees.md
│   │   ├── balanced-tree.md
│   │   ├── binary-search-tree.md
│   │   ├── binary-tree.md
│   │   ├── k-d tree algorithm.md
│   │   └── tree-data-structure.md
│   ├── Tries/
│   │   ├── Problem-Practice.md
│   │   ├── Tries and its Implementation.md
│   │   ├── tries-examples.md
│   │   └── tries-theory.md
│   ├── advance-data-structure/
│   │   ├── _category_.json
│   │   ├── disjoint-set.md
│   │   ├── fenwick-tree.md
│   │   └── segment-tree.md
│   ├── algorithms/
│   │   ├── Bentley-Ottmann-Algorithm/
│   │   │   └── bentley-ottmann-algo.md
│   │   ├── DutchNationalFlag-algorithm/
│   │   │   ├── DutchNationalFlag.md
│   │   │   └── _category_.json
│   │   ├── Encryption algorithms/
│   │   │   ├── Caesar Cipher.md
│   │   │   ├── advanced_encryption_standard.md
│   │   │   ├── asymmetric_encryption.md
│   │   │   ├── blockchain_encryption.md
│   │   │   ├── elliptic_curve_cryptography.md
│   │   │   ├── hashing.md
│   │   │   ├── homomorphic-encryption.md
│   │   │   ├── post-quantum-encryption.md
│   │   │   ├── steganography-algo.md
│   │   │   └── symmetric_encryption.md
│   │   ├── Gale-Shapley-Algorithm/
│   │   │   └── GaleShapley.md
│   │   ├── Scheduling Algorithms/
│   │   │   ├── EarliestDeadlineFirst.md
│   │   │   ├── FirstComeFirstServed.md
│   │   │   ├── LeastRecentlyUsed.md
│   │   │   ├── PriorityScheduling.md
│   │   │   ├── RoundRobin.md
│   │   │   ├── ShortestJobRemainingFirst.md
│   │   │   ├── SweepLine.md
│   │   │   ├── category.json
│   │   │   ├── least-recently-used.md
│   │   │   ├── multilevel-queue-scheduling.md
│   │   │   └── priority-scheduling.md
│   │   ├── Searching Algorithms/
│   │   │   ├── Best-First-Search.md
│   │   │   ├── BinarySearch.md
│   │   │   ├── Breadth-First-Search-(BFS)-Algo.md
│   │   │   ├── Comparison Search.md
│   │   │   ├── Depth-First-Search-(DFS)-Algo.md
│   │   │   ├── DigitalSearch.md
│   │   │   ├── Exponential Search.md
│   │   │   ├── FibbonaciSearch.md
│   │   │   ├── HashingSearch.md
│   │   │   ├── InterpolationSearch.md
│   │   │   ├── JumpSearch.md
│   │   │   ├── LinearSearch.md
│   │   │   ├── Meta-binary-search.md
│   │   │   ├── SentinelSearch.md
│   │   │   └── TernarySearch.md
│   │   ├── Two-Pointers/
│   │   │   ├── IntroductionToTwoPointers.png
│   │   │   ├── Max_Distance.md
│   │   │   ├── Problem-Practice.md
│   │   │   ├── _category_.json
│   │   │   ├── imp-of-two-pointers.md
│   │   │   └── introduction-to-two-pointers.md
│   │   ├── backtracking-algorithms/
│   │   │   ├── _category_.json
│   │   │   ├── backtracking-questions.md
│   │   │   ├── hamilton-path-cyle.md
│   │   │   ├── imp-of-backtracking.md
│   │   │   ├── m-coloring.md
│   │   │   └── what-is-backtracking.md
│   │   ├── greedy-algorithms/
│   │   │   ├── Fractional_Knapsack.md
│   │   │   ├── Huffman-coding.md
│   │   │   ├── Job-sequencing-problem.md
│   │   │   ├── Prim's-Minimum-Spanning-Tree.md
│   │   │   ├── Problem-Practice.md
│   │   │   ├── _category_.json
│   │   │   ├── activity-selection.md
│   │   │   ├── commonly-asked-greedy-questions.md
│   │   │   ├── fractional-knapsack.md
│   │   │   └── greedy-theory.md
│   │   ├── kadane-algorithm/
│   │   │   ├── _category_.json
│   │   │   └── kadane-algo.md
│   │   ├── mathematics-algorithms/
│   │   │   ├── _category_.json
│   │   │   ├── discrete-logarithm.md
│   │   │   ├── fermat-little-theorem.md
│   │   │   ├── gcd-lcm.md
│   │   │   ├── imp-of-mathematics.md
│   │   │   ├── modular-arithmetic.md
│   │   │   ├── sieve-of-eratosthenes.md
│   │   │   ├── sweep-line-algorithm.md
│   │   │   └── what-is-mathematical-algorithms.md
│   │   ├── memoisation-algorithms/
│   │   │   ├── _category_.json
│   │   │   ├── imp-of-memoisation.md
│   │   │   └── what-is-memoisation.md
│   │   ├── moores-voting-algorithm/
│   │   │   └── moore-voting-algo.md
│   │   ├── recursive-algorithms/
│   │   │   ├── DirectRecursion.md
│   │   │   ├── IndirectRecursion.md
│   │   │   ├── _category_.json
│   │   │   ├── mutual-recursion.md
│   │   │   ├── non-tail-recursion.md
│   │   │   ├── tail-recursion.md
│   │   │   └── tree-recursion.md
│   │   ├── sorting-algorithms/
│   │   │   ├── BitonicSort.md
│   │   │   ├── BogoSort.md
│   │   │   ├── BubbleSort.md
│   │   │   ├── BucketSort.md
│   │   │   ├── CocktailShakerSort.md
│   │   │   ├── CombSort.md
│   │   │   ├── CountingSort.md
│   │   │   ├── CycleSort.md
│   │   │   ├── Dutch-flag-algo.md
│   │   │   ├── GnomeSort.md
│   │   │   ├── HeapSort.md
│   │   │   ├── InsertionSort.md
│   │   │   ├── JumpSort.md
│   │   │   ├── MergeSort.md
│   │   │   ├── Odd-Even-Sort.md
│   │   │   ├── OddEvenSort.md
│   │   │   ├── Pancake-sorting-algorithm.md
│   │   │   ├── Pigeonhole.md
│   │   │   ├── QuickSort.md
│   │   │   ├── RadixSort.md
│   │   │   ├── SelectionSort.md
│   │   │   ├── ShellSort.md
│   │   │   ├── StoogeSort.md
│   │   │   ├── TimSort.md
│   │   │   ├── Topological-sorting-algorithm.md
│   │   │   ├── TreeSort.md
│   │   │   ├── _category_.json
│   │   │   ├── odd-even-sorting.md
│   │   │   └── strand-sort.md
│   │   ├── string-algorithm/
│   │   │   ├── Boyer-moore-algorithm.md
│   │   │   ├── Naive-search.md
│   │   │   ├── Suffix-Tree-Algorithm.md
│   │   │   ├── Z-Algorithm.md
│   │   │   ├── aho-corasick-algorithm.md
│   │   │   ├── kmp-algorithm.md
│   │   │   └── rabin-karp-algorithm.md
│   │   ├── string-algorithms/
│   │   │   ├── Naive-String-Matching-Algorithm.md
│   │   │   ├── _category_.json
│   │   │   ├── apostolico-giancarlo-algorithm.md
│   │   │   ├── berry-ravindran-algorithm.md
│   │   │   ├── bitap-algorithm.md
│   │   │   ├── bndm-algorithm.md
│   │   │   ├── boyer-moore-algorithm.md
│   │   │   ├── colussi-algorithm.md
│   │   │   ├── commentz-walter-algorithm.md
│   │   │   ├── crochemores-algorithm.md
│   │   │   ├── finite-state-automation-algorithm.md
│   │   │   ├── kmp-algorithm.md
│   │   │   ├── lcs-algorithm.md
│   │   │   ├── levenshtein-distance-algorithm.md
│   │   │   ├── manacher-algorithm.md
│   │   │   ├── needleman-wunsch-algorithm.md
│   │   │   ├── not-so-naive-algorithm.md
│   │   │   ├── optimal-mismatch-algorithm.md
│   │   │   ├── quick-search-algorithm.md
│   │   │   ├── rabin-karp-algorithm.md
│   │   │   ├── reverse-factor-algorithm.md
│   │   │   ├── shift-or-algorithm.md
│   │   │   ├── simon-algorithm.md
│   │   │   ├── smith-waterman-algorithm.md
│   │   │   ├── suffix-array-algorithm.md
│   │   │   ├── sunday-algorithm.md
│   │   │   ├── turbo-boyer-moore-algorithm.md
│   │   │   ├── two-way-string-matching-algorithm.md
│   │   │   ├── ukkonens-algorithm.md
│   │   │   └── zhu-takaoka-algorithm.md
│   │   ├── CNN-deep-learning-algorithm.md
│   │   ├── Hashing-algorithm.md
│   │   ├── N-Queens-Dynamic-programming-algorithm.md
│   │   ├── Yolo-Object-detection-ML-Algorithm.md
│   │   ├── _category_.json
│   │   └── modular-exponentiation-algorithm.md
│   ├── b-tree/
│   ├── backtracking-algorithms/
│   ├── balancedBinTree/
│   ├── basic-dsa/
│   ├── binary-search-tree/
│   ├── binary-search/
│   ├── binary-trees/
│   ├── bit-manipulation/
│   ├── challenges solutions/
│   ├── combinatorics/
│   ├── complexity/
│   ├── dsa/
│   ├── dynamic-programming/
│   ├── fundamentals/Functions/
│   ├── game-Theory/
│   ├── graphs/
│   ├── greedy-algorithms/
│   ├── hash/
│   ├── heap/
│   ├── knapsack-disaster-relief/
│   ├── languages/
│   ├── linked-list/
│   ├── machine-learning/
│   ├── programming-fundamentals/
│   ├── sortings/
│   ├── content.md
│   └── index.md
 
