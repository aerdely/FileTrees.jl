# Harvest

Reap the fruits of your file trees.

Harvest lets you walk, filter, load, restructure and save directory structures. Loading, processing and saving data can occur in parallel.

There are no restrictions on what files you can read and write, as long as you have functions to work with one file, you can use it to work with a directory of files.

## API

### Tree manipulation

- FileTree
- filter
- merge
- treediff
- flatten
- cp
- mv
- rm
- touch
- mkpath

### Loading, and saving data

- load
- mapvalues
- reducevalues
- save

### Laziness and Parallelism

- lazy
- exec
