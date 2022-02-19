# Classproxy

A simple extension, to set safely the proxy value of CTFPlayer::m_iClass. The detouring of this network property seems popular to fix view models when giving weapons of other classes.
While SendProxy Extension is indeed more flexible than this one, I've received quite a lot of reports that it is currently unstable. And while I do not have time to investigate and fix the other extension, this 'classproxy' extension is provided to ease server operators pain.

Note : This extension doesn't require `sv_parallel_packentities` to be set on 0, you can keep its default value to 1. Which should drastically improve your server performances.