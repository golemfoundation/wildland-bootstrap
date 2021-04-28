# Wildland Bootstrapping Files

Files in this repository might be used to bootstrap _a_ Wildland network. These are primarily manifests for "root" directories, which can be further used to find other users and directories, recursively.

These directories (represented as forests) are similar to DNS root servers, except that in Wildland there is more flexibility in deciding what should be considered a "root directory" for each user. We envision e.g. that different groups might be using different network, perhaps even not inter-connected at all (or connected through a very long path of intermediate directories).

Some of the files here might be partially-encrypted -- in this case these manifests can only be imported by those users, whose pubkeys have been selected by the creator of the manifest.
