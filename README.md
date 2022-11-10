## Dev setup

```
npm install -g json-server
json-server --watch db.json
```

Starts a local dev server on port 3000 with endpoints to mimic the production API.

http://localhost:3000/api/external-engine/work

Then download and put Stockfish binary in the root of the project at filename `stockfish`.

## Run

```
cargo run
```

## Development

Sample stockfish command to see output:

```
./stockfish
position fen rnbqkbnr/pppppppp/8/8/8/8/PPPPPPPP/RNBQKBNR w KQkq - 0 1
go depth 20
```
