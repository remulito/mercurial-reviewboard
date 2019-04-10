# mercurial-reviewboard
[mercurial-reviewboard](https://bitbucket.org/kedder/mercurial-reviewboard) extension version #[aa5f2410de60](https://bitbucket.org/kedder/mercurial-reviewboard/commits/aa5f2410de60) and mercurial client of compatible version **4.6.2**

## Purpose
Because this extension is not compatible with the latest version of mercurial this image is created to allow to use it.

## Here's a basic instruction for getting started.
1. Create mercurial-reviewboard container by run this image and pass path to your mercurial local repository.
```bash
docker run -i -t --rm  -v <your mercurial local repository>:/repository --name hgrb remulito/mercurial-reviewboard
```
2. Navigate to your repository: 
```bash
cd /repository
```
3. Create review request: 
```bash
hg postreview
```
4. See [mercurial-reviewboard](https://bitbucket.org/kedder/mercurial-reviewboard) documentation page for all extension options.
