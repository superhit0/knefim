Build from Source:
- Go to Source Directory.
- Install maven.
- mvn clean package.
- Get Jar from target folder

Using jar:
- java -jar knefim-1.0-jar-with-dependencies.jar -k [int--size-of-k] -i [string-path--input-file] -o [string-path--output-file] -sup [boolean--activate-subtree-pruning] -tm [boolean--activate-transaction-merging] -c [int--maximum-transactions]
- Output Itemsets in output file and stats printed on console.
