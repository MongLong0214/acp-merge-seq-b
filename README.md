# acp-merge-seq-b

Disposable test repository for the Agent Control Plane's multi-repository merge-sequence
acceptance (#240, brought up by #512).

It exists so the sequence can be observed against real GitHub: two repositories merging in a
declared order, with the first repository's post-merge verification gating the second. That
gating cannot be enforced on a Free-tier private repository, which is why this one is public.

Nothing here is a product. Contents are the minimum a post-merge check needs to run.
