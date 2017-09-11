# alpine based cassandra nodetool

The image actually contains a full copy of cassandra. Haven't found a way to install only `nodetool` without cassandra.

# alias
add following alias anywhere you need to run a docker container as default nodetool.

`alias nodetool='docker run --rm -it loivis/nodetool`
