Infinity XYZ Subgraph
TheGraph exposes a GraphQL endpoint to query the events and entities within the Ethereum Smart Chain and Infinity XYZ ecosystem.

Currently, there are multiple subgraphs, but additional subgraphs can be added to this repository, following the current architecture.

Subgraphs
NFT Market (v1): Tracks all Infinity XYZ NFT Market for ERC-721.

Trading Competition (v1): Tracks all metrics for the Easter Battle (April 02—08, 2022).

Dependencies
Graph CLI
Required to generate and build local GraphQL dependencies.
yarn global add @graphprotocol/graph-cli
Deployment
For any of the subgraph: blocks as [subgraph]

Run the cd subgraphs/[subgraph] command to move to the subgraph directory.

Run the yarn codegen command to prepare the TypeScript sources for the GraphQL (generated/\*).

Run the yarn build command to build the subgraph, and check compilation errors before deploying.

Run graph auth --product hosted-service '<ACCESS_TOKEN>'

Deploy via yarn deploy.

v1
To access subgraphs related to Infinity XYZ v1 ecosystem (article), use v1 branch.
