<!-- THIS FILE IS GENERATED VIA '.template-helpers/generate-tag-details.pl' -->

# Tags of `buildpack-deps`

-	[`buildpack-deps:jessie-curl`](#buildpack-depsjessie-curl)
-	[`buildpack-deps:curl`](#buildpack-depscurl)
-	[`buildpack-deps:jessie-scm`](#buildpack-depsjessie-scm)
-	[`buildpack-deps:scm`](#buildpack-depsscm)
-	[`buildpack-deps:jessie`](#buildpack-depsjessie)
-	[`buildpack-deps:latest`](#buildpack-depslatest)
-	[`buildpack-deps:precise-curl`](#buildpack-depsprecise-curl)
-	[`buildpack-deps:precise-scm`](#buildpack-depsprecise-scm)
-	[`buildpack-deps:precise`](#buildpack-depsprecise)
-	[`buildpack-deps:sid-curl`](#buildpack-depssid-curl)
-	[`buildpack-deps:sid-scm`](#buildpack-depssid-scm)
-	[`buildpack-deps:sid`](#buildpack-depssid)
-	[`buildpack-deps:stretch-curl`](#buildpack-depsstretch-curl)
-	[`buildpack-deps:stretch-scm`](#buildpack-depsstretch-scm)
-	[`buildpack-deps:stretch`](#buildpack-depsstretch)
-	[`buildpack-deps:trusty-curl`](#buildpack-depstrusty-curl)
-	[`buildpack-deps:trusty-scm`](#buildpack-depstrusty-scm)
-	[`buildpack-deps:trusty`](#buildpack-depstrusty)
-	[`buildpack-deps:vivid-curl`](#buildpack-depsvivid-curl)
-	[`buildpack-deps:vivid-scm`](#buildpack-depsvivid-scm)
-	[`buildpack-deps:vivid`](#buildpack-depsvivid)
-	[`buildpack-deps:wheezy-curl`](#buildpack-depswheezy-curl)
-	[`buildpack-deps:wheezy-scm`](#buildpack-depswheezy-scm)
-	[`buildpack-deps:wheezy`](#buildpack-depswheezy)
-	[`buildpack-deps:wily-curl`](#buildpack-depswily-curl)
-	[`buildpack-deps:wily-scm`](#buildpack-depswily-scm)
-	[`buildpack-deps:wily`](#buildpack-depswily)

## `buildpack-deps:jessie-curl`

```console
$ docker pull library/buildpack-deps@sha256:3014e866d9296bd4fa6123f68d4755a44e9157cb3133a267afe4814ca5257283
```

-	Total Virtual Size: 169.4 MB (169408770 bytes)
-	Total v2 Content-Length: 69.9 MB (69882917 bytes)

### Layers (3)

#### `6d1ae97ee388924068b7a4797d995d57d1e6194843e7e2178e592a880bf6c7ad`

```dockerfile
ADD file:863d6edd178364362a93f49103aa75c1bd03a37e83bfe0b051a3881c9333d238 in /
```

-	Created: Fri, 04 Dec 2015 19:27:57 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 125.1 MB (125115267 bytes)
-	v2 Blob: `sha256:d4bce7fd68df2e8bb04e317e7cb7899e981159a4da89339e38c8bf30e6c318f0`
-	v2 Content-Length: 51.4 MB (51354256 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 19:45:49 GMT

#### `8b9a99209d5c8f3fc5b4c01573f0508d1ddaa01c4f83c587e03b67497566aab9`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Fri, 04 Dec 2015 19:28:00 GMT
-	Parent Layer: `6d1ae97ee388924068b7a4797d995d57d1e6194843e7e2178e592a880bf6c7ad`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2e05a52ffd47e52854ef8b2d0989e08d41301926baf7b3aeb8d5c370e0b11566`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:32:32 GMT
-	Parent Layer: `8b9a99209d5c8f3fc5b4c01573f0508d1ddaa01c4f83c587e03b67497566aab9`
-	Docker Version: 1.8.3
-	Virtual Size: 44.3 MB (44293503 bytes)
-	v2 Blob: `sha256:816152842605fe3ede1dc7c47f33e641f74cb4ae0d5c51a6c19cc8d85da934f3`
-	v2 Content-Length: 18.5 MB (18528629 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 19:56:45 GMT

## `buildpack-deps:curl`

```console
$ docker pull library/buildpack-deps@sha256:5045624d7158276a2da4768ae3b46601a373c93f314d2549e4171c5b87f3941b
```

-	Total Virtual Size: 169.4 MB (169408770 bytes)
-	Total v2 Content-Length: 69.9 MB (69882917 bytes)

### Layers (3)

#### `6d1ae97ee388924068b7a4797d995d57d1e6194843e7e2178e592a880bf6c7ad`

```dockerfile
ADD file:863d6edd178364362a93f49103aa75c1bd03a37e83bfe0b051a3881c9333d238 in /
```

-	Created: Fri, 04 Dec 2015 19:27:57 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 125.1 MB (125115267 bytes)
-	v2 Blob: `sha256:d4bce7fd68df2e8bb04e317e7cb7899e981159a4da89339e38c8bf30e6c318f0`
-	v2 Content-Length: 51.4 MB (51354256 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 19:45:49 GMT

#### `8b9a99209d5c8f3fc5b4c01573f0508d1ddaa01c4f83c587e03b67497566aab9`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Fri, 04 Dec 2015 19:28:00 GMT
-	Parent Layer: `6d1ae97ee388924068b7a4797d995d57d1e6194843e7e2178e592a880bf6c7ad`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2e05a52ffd47e52854ef8b2d0989e08d41301926baf7b3aeb8d5c370e0b11566`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:32:32 GMT
-	Parent Layer: `8b9a99209d5c8f3fc5b4c01573f0508d1ddaa01c4f83c587e03b67497566aab9`
-	Docker Version: 1.8.3
-	Virtual Size: 44.3 MB (44293503 bytes)
-	v2 Blob: `sha256:816152842605fe3ede1dc7c47f33e641f74cb4ae0d5c51a6c19cc8d85da934f3`
-	v2 Content-Length: 18.5 MB (18528629 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 19:56:45 GMT

## `buildpack-deps:jessie-scm`

```console
$ docker pull library/buildpack-deps@sha256:89774b5f71893e9dac2631635dd32b3ec34be5363861cd582dc665847573b3f6
```

-	Total Virtual Size: 291.7 MB (291658597 bytes)
-	Total v2 Content-Length: 112.2 MB (112207444 bytes)

### Layers (4)

#### `6d1ae97ee388924068b7a4797d995d57d1e6194843e7e2178e592a880bf6c7ad`

```dockerfile
ADD file:863d6edd178364362a93f49103aa75c1bd03a37e83bfe0b051a3881c9333d238 in /
```

-	Created: Fri, 04 Dec 2015 19:27:57 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 125.1 MB (125115267 bytes)
-	v2 Blob: `sha256:d4bce7fd68df2e8bb04e317e7cb7899e981159a4da89339e38c8bf30e6c318f0`
-	v2 Content-Length: 51.4 MB (51354256 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 19:45:49 GMT

#### `8b9a99209d5c8f3fc5b4c01573f0508d1ddaa01c4f83c587e03b67497566aab9`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Fri, 04 Dec 2015 19:28:00 GMT
-	Parent Layer: `6d1ae97ee388924068b7a4797d995d57d1e6194843e7e2178e592a880bf6c7ad`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2e05a52ffd47e52854ef8b2d0989e08d41301926baf7b3aeb8d5c370e0b11566`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:32:32 GMT
-	Parent Layer: `8b9a99209d5c8f3fc5b4c01573f0508d1ddaa01c4f83c587e03b67497566aab9`
-	Docker Version: 1.8.3
-	Virtual Size: 44.3 MB (44293503 bytes)
-	v2 Blob: `sha256:816152842605fe3ede1dc7c47f33e641f74cb4ae0d5c51a6c19cc8d85da934f3`
-	v2 Content-Length: 18.5 MB (18528629 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 19:56:45 GMT

#### `80887d1455318f25f3adaee1f9a584a3482ccec4b2a17d8891066d214c241da1`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:33:37 GMT
-	Parent Layer: `2e05a52ffd47e52854ef8b2d0989e08d41301926baf7b3aeb8d5c370e0b11566`
-	Docker Version: 1.8.3
-	Virtual Size: 122.2 MB (122249827 bytes)
-	v2 Blob: `sha256:5dcab2c7e430ea37e464f192c3e1b05476e4378af0ad362d932e03921b59c972`
-	v2 Content-Length: 42.3 MB (42324527 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 19:58:25 GMT

## `buildpack-deps:scm`

```console
$ docker pull library/buildpack-deps@sha256:3c477cb380ae6802f70665a51c8b65cb148f69ac8af213dbe78076e4ea29a04b
```

-	Total Virtual Size: 291.7 MB (291658597 bytes)
-	Total v2 Content-Length: 112.2 MB (112207444 bytes)

### Layers (4)

#### `6d1ae97ee388924068b7a4797d995d57d1e6194843e7e2178e592a880bf6c7ad`

```dockerfile
ADD file:863d6edd178364362a93f49103aa75c1bd03a37e83bfe0b051a3881c9333d238 in /
```

-	Created: Fri, 04 Dec 2015 19:27:57 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 125.1 MB (125115267 bytes)
-	v2 Blob: `sha256:d4bce7fd68df2e8bb04e317e7cb7899e981159a4da89339e38c8bf30e6c318f0`
-	v2 Content-Length: 51.4 MB (51354256 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 19:45:49 GMT

#### `8b9a99209d5c8f3fc5b4c01573f0508d1ddaa01c4f83c587e03b67497566aab9`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Fri, 04 Dec 2015 19:28:00 GMT
-	Parent Layer: `6d1ae97ee388924068b7a4797d995d57d1e6194843e7e2178e592a880bf6c7ad`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2e05a52ffd47e52854ef8b2d0989e08d41301926baf7b3aeb8d5c370e0b11566`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:32:32 GMT
-	Parent Layer: `8b9a99209d5c8f3fc5b4c01573f0508d1ddaa01c4f83c587e03b67497566aab9`
-	Docker Version: 1.8.3
-	Virtual Size: 44.3 MB (44293503 bytes)
-	v2 Blob: `sha256:816152842605fe3ede1dc7c47f33e641f74cb4ae0d5c51a6c19cc8d85da934f3`
-	v2 Content-Length: 18.5 MB (18528629 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 19:56:45 GMT

#### `80887d1455318f25f3adaee1f9a584a3482ccec4b2a17d8891066d214c241da1`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:33:37 GMT
-	Parent Layer: `2e05a52ffd47e52854ef8b2d0989e08d41301926baf7b3aeb8d5c370e0b11566`
-	Docker Version: 1.8.3
-	Virtual Size: 122.2 MB (122249827 bytes)
-	v2 Blob: `sha256:5dcab2c7e430ea37e464f192c3e1b05476e4378af0ad362d932e03921b59c972`
-	v2 Content-Length: 42.3 MB (42324527 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 19:58:25 GMT

## `buildpack-deps:jessie`

```console
$ docker pull library/buildpack-deps@sha256:ae0f882c043e80e01f399084c52c4f878f043cc29e75c95bd64da8711bd20d0b
```

-	Total Virtual Size: 606.3 MB (606284916 bytes)
-	Total v2 Content-Length: 240.8 MB (240761195 bytes)

### Layers (5)

#### `6d1ae97ee388924068b7a4797d995d57d1e6194843e7e2178e592a880bf6c7ad`

```dockerfile
ADD file:863d6edd178364362a93f49103aa75c1bd03a37e83bfe0b051a3881c9333d238 in /
```

-	Created: Fri, 04 Dec 2015 19:27:57 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 125.1 MB (125115267 bytes)
-	v2 Blob: `sha256:d4bce7fd68df2e8bb04e317e7cb7899e981159a4da89339e38c8bf30e6c318f0`
-	v2 Content-Length: 51.4 MB (51354256 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 19:45:49 GMT

#### `8b9a99209d5c8f3fc5b4c01573f0508d1ddaa01c4f83c587e03b67497566aab9`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Fri, 04 Dec 2015 19:28:00 GMT
-	Parent Layer: `6d1ae97ee388924068b7a4797d995d57d1e6194843e7e2178e592a880bf6c7ad`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2e05a52ffd47e52854ef8b2d0989e08d41301926baf7b3aeb8d5c370e0b11566`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:32:32 GMT
-	Parent Layer: `8b9a99209d5c8f3fc5b4c01573f0508d1ddaa01c4f83c587e03b67497566aab9`
-	Docker Version: 1.8.3
-	Virtual Size: 44.3 MB (44293503 bytes)
-	v2 Blob: `sha256:816152842605fe3ede1dc7c47f33e641f74cb4ae0d5c51a6c19cc8d85da934f3`
-	v2 Content-Length: 18.5 MB (18528629 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 19:56:45 GMT

#### `80887d1455318f25f3adaee1f9a584a3482ccec4b2a17d8891066d214c241da1`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:33:37 GMT
-	Parent Layer: `2e05a52ffd47e52854ef8b2d0989e08d41301926baf7b3aeb8d5c370e0b11566`
-	Docker Version: 1.8.3
-	Virtual Size: 122.2 MB (122249827 bytes)
-	v2 Blob: `sha256:5dcab2c7e430ea37e464f192c3e1b05476e4378af0ad362d932e03921b59c972`
-	v2 Content-Length: 42.3 MB (42324527 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 19:58:25 GMT

#### `efccf6dd12d43929909fd40d5847de568bbb6bc1250d4cdd60424c4b04356bd8`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:35:34 GMT
-	Parent Layer: `80887d1455318f25f3adaee1f9a584a3482ccec4b2a17d8891066d214c241da1`
-	Docker Version: 1.8.3
-	Virtual Size: 314.6 MB (314626319 bytes)
-	v2 Blob: `sha256:dc54ada22a60efb50d419685f87d5d5f43572ac73e1596e94bbbb08b2aab42a4`
-	v2 Content-Length: 128.6 MB (128553751 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 19:59:57 GMT

## `buildpack-deps:latest`

```console
$ docker pull library/buildpack-deps@sha256:3a5ea1cdc7b82a3d717e3d403dd1d540d696c21abc18dc70af6097a2e4cdef03
```

-	Total Virtual Size: 606.3 MB (606284916 bytes)
-	Total v2 Content-Length: 240.8 MB (240761195 bytes)

### Layers (5)

#### `6d1ae97ee388924068b7a4797d995d57d1e6194843e7e2178e592a880bf6c7ad`

```dockerfile
ADD file:863d6edd178364362a93f49103aa75c1bd03a37e83bfe0b051a3881c9333d238 in /
```

-	Created: Fri, 04 Dec 2015 19:27:57 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 125.1 MB (125115267 bytes)
-	v2 Blob: `sha256:d4bce7fd68df2e8bb04e317e7cb7899e981159a4da89339e38c8bf30e6c318f0`
-	v2 Content-Length: 51.4 MB (51354256 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 19:45:49 GMT

#### `8b9a99209d5c8f3fc5b4c01573f0508d1ddaa01c4f83c587e03b67497566aab9`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Fri, 04 Dec 2015 19:28:00 GMT
-	Parent Layer: `6d1ae97ee388924068b7a4797d995d57d1e6194843e7e2178e592a880bf6c7ad`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `2e05a52ffd47e52854ef8b2d0989e08d41301926baf7b3aeb8d5c370e0b11566`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:32:32 GMT
-	Parent Layer: `8b9a99209d5c8f3fc5b4c01573f0508d1ddaa01c4f83c587e03b67497566aab9`
-	Docker Version: 1.8.3
-	Virtual Size: 44.3 MB (44293503 bytes)
-	v2 Blob: `sha256:816152842605fe3ede1dc7c47f33e641f74cb4ae0d5c51a6c19cc8d85da934f3`
-	v2 Content-Length: 18.5 MB (18528629 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 19:56:45 GMT

#### `80887d1455318f25f3adaee1f9a584a3482ccec4b2a17d8891066d214c241da1`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:33:37 GMT
-	Parent Layer: `2e05a52ffd47e52854ef8b2d0989e08d41301926baf7b3aeb8d5c370e0b11566`
-	Docker Version: 1.8.3
-	Virtual Size: 122.2 MB (122249827 bytes)
-	v2 Blob: `sha256:5dcab2c7e430ea37e464f192c3e1b05476e4378af0ad362d932e03921b59c972`
-	v2 Content-Length: 42.3 MB (42324527 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 19:58:25 GMT

#### `efccf6dd12d43929909fd40d5847de568bbb6bc1250d4cdd60424c4b04356bd8`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:35:34 GMT
-	Parent Layer: `80887d1455318f25f3adaee1f9a584a3482ccec4b2a17d8891066d214c241da1`
-	Docker Version: 1.8.3
-	Virtual Size: 314.6 MB (314626319 bytes)
-	v2 Blob: `sha256:dc54ada22a60efb50d419685f87d5d5f43572ac73e1596e94bbbb08b2aab42a4`
-	v2 Content-Length: 128.6 MB (128553751 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 19:59:57 GMT

## `buildpack-deps:precise-curl`

```console
$ docker pull library/buildpack-deps@sha256:b4f38375a9733ee264f220a24dff9eac977432e7b5652347f3063e503df244b7
```

-	Total Virtual Size: 147.6 MB (147606813 bytes)
-	Total v2 Content-Length: 49.2 MB (49198430 bytes)

### Layers (5)

#### `e31e0d7aee0f34af6f896fd941ceb052d2cf40cb6661df1f86d2ee01bd24cde1`

```dockerfile
ADD file:4a9e089e81d6581a5427d5b163488da9de691cdc13e91ecec09c0ca41787659d in /
```

-	Created: Tue, 10 Nov 2015 00:34:01 GMT
-	Docker Version: 1.9.0
-	Virtual Size: 135.9 MB (135908010 bytes)
-	v2 Blob: `sha256:435246b0a5011ea70ff7d93bced7af398bfa417e2d845b762f36f513ba2ab458`
-	v2 Content-Length: 44.0 MB (44038298 bytes)
-	v2 Last-Modified: Tue, 10 Nov 2015 18:01:06 GMT

#### `5bc08cfeaf2ba4931bc9d54351cce660759e3fc20c2b2cb8ef6b8ec0d8116787`

```dockerfile
RUN echo '#!/bin/sh' > /usr/sbin/policy-rc.d \
	&& echo 'exit 101' >> /usr/sbin/policy-rc.d \
	&& chmod +x /usr/sbin/policy-rc.d \
		&& dpkg-divert --local --rename --add /sbin/initctl \
	&& cp -a /usr/sbin/policy-rc.d /sbin/initctl \
	&& sed -i 's/^exit.*/exit 0/' /sbin/initctl \
		&& echo 'force-unsafe-io' > /etc/dpkg/dpkg.cfg.d/docker-apt-speedup \
		&& echo 'DPkg::Post-Invoke { "rm -f /var/cache/apt/archives/*.deb /var/cache/apt/archives/partial/*.deb /var/cache/apt/*.bin || true"; };' > /etc/apt/apt.conf.d/docker-clean \
	&& echo 'APT::Update::Post-Invoke { "rm -f /var/cache/apt/archives/*.deb /var/cache/apt/archives/partial/*.deb /var/cache/apt/*.bin || true"; };' >> /etc/apt/apt.conf.d/docker-clean \
	&& echo 'Dir::Cache::pkgcache ""; Dir::Cache::srcpkgcache "";' >> /etc/apt/apt.conf.d/docker-clean \
		&& echo 'Acquire::Languages "none";' > /etc/apt/apt.conf.d/docker-no-languages \
		&& echo 'Acquire::GzipIndexes "true"; Acquire::CompressionTypes::Order:: "gz";' > /etc/apt/apt.conf.d/docker-gzip-indexes
```

-	Created: Tue, 10 Nov 2015 00:34:04 GMT
-	Parent Layer: `e31e0d7aee0f34af6f896fd941ceb052d2cf40cb6661df1f86d2ee01bd24cde1`
-	Docker Version: 1.9.0
-	Virtual Size: 156.2 KB (156213 bytes)
-	v2 Blob: `sha256:62a965d5eb1111d15f226f9cac2f763d70cf03113367d7b7bc0f43c6bba9724d`
-	v2 Content-Length: 57.9 KB (57868 bytes)
-	v2 Last-Modified: Tue, 10 Nov 2015 18:00:46 GMT

#### `259b021ba9cd3ed978d537d7f65f4d2f4a080787b778a8ad46b0122e2d769a54`

```dockerfile
RUN sed -i 's/^#\s*\(deb.*universe\)$/\1/g' /etc/apt/sources.list
```

-	Created: Tue, 10 Nov 2015 00:34:06 GMT
-	Parent Layer: `5bc08cfeaf2ba4931bc9d54351cce660759e3fc20c2b2cb8ef6b8ec0d8116787`
-	Docker Version: 1.9.0
-	Virtual Size: 1.9 KB (1911 bytes)
-	v2 Blob: `sha256:1dfcf00db2dc27565d11a7abee9c1b78efa8e646dc8f63b70f6b91f6e1a7da0b`
-	v2 Content-Length: 680.0 B
-	v2 Last-Modified: Tue, 10 Nov 2015 18:00:42 GMT

#### `04c3793b12299e58bb9c47bc75a51dfb0e0421a97a319d1fc897e430bd44af58`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 10 Nov 2015 00:34:06 GMT
-	Parent Layer: `259b021ba9cd3ed978d537d7f65f4d2f4a080787b778a8ad46b0122e2d769a54`
-	Docker Version: 1.9.0
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `e3d25699ff8e4c5c4c589325f99229427d637cd53e9535d84a00b047dad5404c`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 10 Nov 2015 17:30:40 GMT
-	Parent Layer: `04c3793b12299e58bb9c47bc75a51dfb0e0421a97a319d1fc897e430bd44af58`
-	Docker Version: 1.9.0
-	Virtual Size: 11.5 MB (11540679 bytes)
-	v2 Blob: `sha256:1bff0cb265004a6c3dffad02eadb63fe681c422e8b968033d870e9c7577cc59d`
-	v2 Content-Length: 5.1 MB (5101552 bytes)
-	v2 Last-Modified: Tue, 10 Nov 2015 18:11:32 GMT

## `buildpack-deps:precise-scm`

```console
$ docker pull library/buildpack-deps@sha256:844d7be857b3bf59c7fc1cbd823ed510553a5989736673c7cd82d0a036a8422e
```

-	Total Virtual Size: 241.9 MB (241930590 bytes)
-	Total v2 Content-Length: 80.0 MB (80024001 bytes)

### Layers (6)

#### `e31e0d7aee0f34af6f896fd941ceb052d2cf40cb6661df1f86d2ee01bd24cde1`

```dockerfile
ADD file:4a9e089e81d6581a5427d5b163488da9de691cdc13e91ecec09c0ca41787659d in /
```

-	Created: Tue, 10 Nov 2015 00:34:01 GMT
-	Docker Version: 1.9.0
-	Virtual Size: 135.9 MB (135908010 bytes)
-	v2 Blob: `sha256:435246b0a5011ea70ff7d93bced7af398bfa417e2d845b762f36f513ba2ab458`
-	v2 Content-Length: 44.0 MB (44038298 bytes)
-	v2 Last-Modified: Tue, 10 Nov 2015 18:01:06 GMT

#### `5bc08cfeaf2ba4931bc9d54351cce660759e3fc20c2b2cb8ef6b8ec0d8116787`

```dockerfile
RUN echo '#!/bin/sh' > /usr/sbin/policy-rc.d \
	&& echo 'exit 101' >> /usr/sbin/policy-rc.d \
	&& chmod +x /usr/sbin/policy-rc.d \
		&& dpkg-divert --local --rename --add /sbin/initctl \
	&& cp -a /usr/sbin/policy-rc.d /sbin/initctl \
	&& sed -i 's/^exit.*/exit 0/' /sbin/initctl \
		&& echo 'force-unsafe-io' > /etc/dpkg/dpkg.cfg.d/docker-apt-speedup \
		&& echo 'DPkg::Post-Invoke { "rm -f /var/cache/apt/archives/*.deb /var/cache/apt/archives/partial/*.deb /var/cache/apt/*.bin || true"; };' > /etc/apt/apt.conf.d/docker-clean \
	&& echo 'APT::Update::Post-Invoke { "rm -f /var/cache/apt/archives/*.deb /var/cache/apt/archives/partial/*.deb /var/cache/apt/*.bin || true"; };' >> /etc/apt/apt.conf.d/docker-clean \
	&& echo 'Dir::Cache::pkgcache ""; Dir::Cache::srcpkgcache "";' >> /etc/apt/apt.conf.d/docker-clean \
		&& echo 'Acquire::Languages "none";' > /etc/apt/apt.conf.d/docker-no-languages \
		&& echo 'Acquire::GzipIndexes "true"; Acquire::CompressionTypes::Order:: "gz";' > /etc/apt/apt.conf.d/docker-gzip-indexes
```

-	Created: Tue, 10 Nov 2015 00:34:04 GMT
-	Parent Layer: `e31e0d7aee0f34af6f896fd941ceb052d2cf40cb6661df1f86d2ee01bd24cde1`
-	Docker Version: 1.9.0
-	Virtual Size: 156.2 KB (156213 bytes)
-	v2 Blob: `sha256:62a965d5eb1111d15f226f9cac2f763d70cf03113367d7b7bc0f43c6bba9724d`
-	v2 Content-Length: 57.9 KB (57868 bytes)
-	v2 Last-Modified: Tue, 10 Nov 2015 18:00:46 GMT

#### `259b021ba9cd3ed978d537d7f65f4d2f4a080787b778a8ad46b0122e2d769a54`

```dockerfile
RUN sed -i 's/^#\s*\(deb.*universe\)$/\1/g' /etc/apt/sources.list
```

-	Created: Tue, 10 Nov 2015 00:34:06 GMT
-	Parent Layer: `5bc08cfeaf2ba4931bc9d54351cce660759e3fc20c2b2cb8ef6b8ec0d8116787`
-	Docker Version: 1.9.0
-	Virtual Size: 1.9 KB (1911 bytes)
-	v2 Blob: `sha256:1dfcf00db2dc27565d11a7abee9c1b78efa8e646dc8f63b70f6b91f6e1a7da0b`
-	v2 Content-Length: 680.0 B
-	v2 Last-Modified: Tue, 10 Nov 2015 18:00:42 GMT

#### `04c3793b12299e58bb9c47bc75a51dfb0e0421a97a319d1fc897e430bd44af58`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 10 Nov 2015 00:34:06 GMT
-	Parent Layer: `259b021ba9cd3ed978d537d7f65f4d2f4a080787b778a8ad46b0122e2d769a54`
-	Docker Version: 1.9.0
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `e3d25699ff8e4c5c4c589325f99229427d637cd53e9535d84a00b047dad5404c`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 10 Nov 2015 17:30:40 GMT
-	Parent Layer: `04c3793b12299e58bb9c47bc75a51dfb0e0421a97a319d1fc897e430bd44af58`
-	Docker Version: 1.9.0
-	Virtual Size: 11.5 MB (11540679 bytes)
-	v2 Blob: `sha256:1bff0cb265004a6c3dffad02eadb63fe681c422e8b968033d870e9c7577cc59d`
-	v2 Content-Length: 5.1 MB (5101552 bytes)
-	v2 Last-Modified: Tue, 10 Nov 2015 18:11:32 GMT

#### `f4c1cb7e5f8f00d53cc530279d228240cdbd4a38ff7b0a0e9b042a75a11b29b0`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Wed, 25 Nov 2015 16:51:49 GMT
-	Parent Layer: `e3d25699ff8e4c5c4c589325f99229427d637cd53e9535d84a00b047dad5404c`
-	Docker Version: 1.8.3
-	Virtual Size: 94.3 MB (94323777 bytes)
-	v2 Blob: `sha256:4f23e27417ae7522c252fee9fae539ac130ca5c132e49f863d7d7e0b9d0a78e9`
-	v2 Content-Length: 30.8 MB (30825571 bytes)
-	v2 Last-Modified: Wed, 25 Nov 2015 18:01:58 GMT

## `buildpack-deps:precise`

```console
$ docker pull library/buildpack-deps@sha256:67eb9f696e8f734c37352c3c9314bf9e909ca6828d9c4729fb624655f84c2359
```

-	Total Virtual Size: 491.8 MB (491773385 bytes)
-	Total v2 Content-Length: 162.0 MB (161968671 bytes)

### Layers (7)

#### `e31e0d7aee0f34af6f896fd941ceb052d2cf40cb6661df1f86d2ee01bd24cde1`

```dockerfile
ADD file:4a9e089e81d6581a5427d5b163488da9de691cdc13e91ecec09c0ca41787659d in /
```

-	Created: Tue, 10 Nov 2015 00:34:01 GMT
-	Docker Version: 1.9.0
-	Virtual Size: 135.9 MB (135908010 bytes)
-	v2 Blob: `sha256:435246b0a5011ea70ff7d93bced7af398bfa417e2d845b762f36f513ba2ab458`
-	v2 Content-Length: 44.0 MB (44038298 bytes)
-	v2 Last-Modified: Tue, 10 Nov 2015 18:01:06 GMT

#### `5bc08cfeaf2ba4931bc9d54351cce660759e3fc20c2b2cb8ef6b8ec0d8116787`

```dockerfile
RUN echo '#!/bin/sh' > /usr/sbin/policy-rc.d \
	&& echo 'exit 101' >> /usr/sbin/policy-rc.d \
	&& chmod +x /usr/sbin/policy-rc.d \
		&& dpkg-divert --local --rename --add /sbin/initctl \
	&& cp -a /usr/sbin/policy-rc.d /sbin/initctl \
	&& sed -i 's/^exit.*/exit 0/' /sbin/initctl \
		&& echo 'force-unsafe-io' > /etc/dpkg/dpkg.cfg.d/docker-apt-speedup \
		&& echo 'DPkg::Post-Invoke { "rm -f /var/cache/apt/archives/*.deb /var/cache/apt/archives/partial/*.deb /var/cache/apt/*.bin || true"; };' > /etc/apt/apt.conf.d/docker-clean \
	&& echo 'APT::Update::Post-Invoke { "rm -f /var/cache/apt/archives/*.deb /var/cache/apt/archives/partial/*.deb /var/cache/apt/*.bin || true"; };' >> /etc/apt/apt.conf.d/docker-clean \
	&& echo 'Dir::Cache::pkgcache ""; Dir::Cache::srcpkgcache "";' >> /etc/apt/apt.conf.d/docker-clean \
		&& echo 'Acquire::Languages "none";' > /etc/apt/apt.conf.d/docker-no-languages \
		&& echo 'Acquire::GzipIndexes "true"; Acquire::CompressionTypes::Order:: "gz";' > /etc/apt/apt.conf.d/docker-gzip-indexes
```

-	Created: Tue, 10 Nov 2015 00:34:04 GMT
-	Parent Layer: `e31e0d7aee0f34af6f896fd941ceb052d2cf40cb6661df1f86d2ee01bd24cde1`
-	Docker Version: 1.9.0
-	Virtual Size: 156.2 KB (156213 bytes)
-	v2 Blob: `sha256:62a965d5eb1111d15f226f9cac2f763d70cf03113367d7b7bc0f43c6bba9724d`
-	v2 Content-Length: 57.9 KB (57868 bytes)
-	v2 Last-Modified: Tue, 10 Nov 2015 18:00:46 GMT

#### `259b021ba9cd3ed978d537d7f65f4d2f4a080787b778a8ad46b0122e2d769a54`

```dockerfile
RUN sed -i 's/^#\s*\(deb.*universe\)$/\1/g' /etc/apt/sources.list
```

-	Created: Tue, 10 Nov 2015 00:34:06 GMT
-	Parent Layer: `5bc08cfeaf2ba4931bc9d54351cce660759e3fc20c2b2cb8ef6b8ec0d8116787`
-	Docker Version: 1.9.0
-	Virtual Size: 1.9 KB (1911 bytes)
-	v2 Blob: `sha256:1dfcf00db2dc27565d11a7abee9c1b78efa8e646dc8f63b70f6b91f6e1a7da0b`
-	v2 Content-Length: 680.0 B
-	v2 Last-Modified: Tue, 10 Nov 2015 18:00:42 GMT

#### `04c3793b12299e58bb9c47bc75a51dfb0e0421a97a319d1fc897e430bd44af58`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 10 Nov 2015 00:34:06 GMT
-	Parent Layer: `259b021ba9cd3ed978d537d7f65f4d2f4a080787b778a8ad46b0122e2d769a54`
-	Docker Version: 1.9.0
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `e3d25699ff8e4c5c4c589325f99229427d637cd53e9535d84a00b047dad5404c`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 10 Nov 2015 17:30:40 GMT
-	Parent Layer: `04c3793b12299e58bb9c47bc75a51dfb0e0421a97a319d1fc897e430bd44af58`
-	Docker Version: 1.9.0
-	Virtual Size: 11.5 MB (11540679 bytes)
-	v2 Blob: `sha256:1bff0cb265004a6c3dffad02eadb63fe681c422e8b968033d870e9c7577cc59d`
-	v2 Content-Length: 5.1 MB (5101552 bytes)
-	v2 Last-Modified: Tue, 10 Nov 2015 18:11:32 GMT

#### `f4c1cb7e5f8f00d53cc530279d228240cdbd4a38ff7b0a0e9b042a75a11b29b0`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Wed, 25 Nov 2015 16:51:49 GMT
-	Parent Layer: `e3d25699ff8e4c5c4c589325f99229427d637cd53e9535d84a00b047dad5404c`
-	Docker Version: 1.8.3
-	Virtual Size: 94.3 MB (94323777 bytes)
-	v2 Blob: `sha256:4f23e27417ae7522c252fee9fae539ac130ca5c132e49f863d7d7e0b9d0a78e9`
-	v2 Content-Length: 30.8 MB (30825571 bytes)
-	v2 Last-Modified: Wed, 25 Nov 2015 18:01:58 GMT

#### `21ff44474cfd70d2fcf26e7553c82a3ebb37643876c491d9c1c3d544fba86fb4`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Wed, 25 Nov 2015 16:53:03 GMT
-	Parent Layer: `f4c1cb7e5f8f00d53cc530279d228240cdbd4a38ff7b0a0e9b042a75a11b29b0`
-	Docker Version: 1.8.3
-	Virtual Size: 249.8 MB (249842795 bytes)
-	v2 Blob: `sha256:30755053263585ba6991191d0b839bbf398f048b24b1ed724a2f1c88259a3a50`
-	v2 Content-Length: 81.9 MB (81944670 bytes)
-	v2 Last-Modified: Wed, 25 Nov 2015 18:03:22 GMT

## `buildpack-deps:sid-curl`

```console
$ docker pull library/buildpack-deps@sha256:d9d414f4e7ef0ae06f1fe2dfea4db0abe49218a7fb128524553b477a2db928d5
```

-	Total Virtual Size: 165.5 MB (165465020 bytes)
-	Total v2 Content-Length: 72.0 MB (72009226 bytes)

### Layers (3)

#### `0f505133a3b99502340358a20826acfa5d43b6ef7e2b64ad5ddfc8f0fac5c855`

```dockerfile
ADD file:113653a4a76ebce4343758a16fbbb22ccc40b4ed9285eb62de9775d94b110a31 in /
```

-	Created: Fri, 04 Dec 2015 19:29:17 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 116.7 MB (116711866 bytes)
-	v2 Blob: `sha256:db77e04b88e12d6724c93949d09dce661a66719fe0c819b5f66a5332037dd328`
-	v2 Content-Length: 51.7 MB (51657474 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 19:48:45 GMT

#### `20b3d0655ab649aa47ab2a073239b980590f99945f78e562173de756ad63d3da`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Fri, 04 Dec 2015 19:29:42 GMT
-	Parent Layer: `0f505133a3b99502340358a20826acfa5d43b6ef7e2b64ad5ddfc8f0fac5c855`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `7d0fa6f23d25a8eda5baf81f34605892e3d0cb3993b29ea7fd1e34d4f0fe3c8c`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:36:16 GMT
-	Parent Layer: `20b3d0655ab649aa47ab2a073239b980590f99945f78e562173de756ad63d3da`
-	Docker Version: 1.8.3
-	Virtual Size: 48.8 MB (48753154 bytes)
-	v2 Blob: `sha256:eba085212fbf6e68c7eff37a948f7042f1fb2c870fedcba765b8cb965ab51c81`
-	v2 Content-Length: 20.4 MB (20351720 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 20:01:55 GMT

## `buildpack-deps:sid-scm`

```console
$ docker pull library/buildpack-deps@sha256:e8873fca7ca713de1b49cf2f765370eb4662243c9dd111bebddce4561d07e6d4
```

-	Total Virtual Size: 293.6 MB (293644061 bytes)
-	Total v2 Content-Length: 116.6 MB (116637246 bytes)

### Layers (4)

#### `0f505133a3b99502340358a20826acfa5d43b6ef7e2b64ad5ddfc8f0fac5c855`

```dockerfile
ADD file:113653a4a76ebce4343758a16fbbb22ccc40b4ed9285eb62de9775d94b110a31 in /
```

-	Created: Fri, 04 Dec 2015 19:29:17 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 116.7 MB (116711866 bytes)
-	v2 Blob: `sha256:db77e04b88e12d6724c93949d09dce661a66719fe0c819b5f66a5332037dd328`
-	v2 Content-Length: 51.7 MB (51657474 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 19:48:45 GMT

#### `20b3d0655ab649aa47ab2a073239b980590f99945f78e562173de756ad63d3da`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Fri, 04 Dec 2015 19:29:42 GMT
-	Parent Layer: `0f505133a3b99502340358a20826acfa5d43b6ef7e2b64ad5ddfc8f0fac5c855`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `7d0fa6f23d25a8eda5baf81f34605892e3d0cb3993b29ea7fd1e34d4f0fe3c8c`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:36:16 GMT
-	Parent Layer: `20b3d0655ab649aa47ab2a073239b980590f99945f78e562173de756ad63d3da`
-	Docker Version: 1.8.3
-	Virtual Size: 48.8 MB (48753154 bytes)
-	v2 Blob: `sha256:eba085212fbf6e68c7eff37a948f7042f1fb2c870fedcba765b8cb965ab51c81`
-	v2 Content-Length: 20.4 MB (20351720 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 20:01:55 GMT

#### `6de76ee12a14900325ad14e01f77abcd935801a1b862e0ddb1c6813e47bfed11`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:36:42 GMT
-	Parent Layer: `7d0fa6f23d25a8eda5baf81f34605892e3d0cb3993b29ea7fd1e34d4f0fe3c8c`
-	Docker Version: 1.8.3
-	Virtual Size: 128.2 MB (128179041 bytes)
-	v2 Blob: `sha256:9b9f23286c2453295057de9b1248ccf80b54ca95ccde49f1b095e983b9e9b7ff`
-	v2 Content-Length: 44.6 MB (44628020 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 20:03:30 GMT

## `buildpack-deps:sid`

```console
$ docker pull library/buildpack-deps@sha256:cdcb5d8cb0287071d24796c9e8be05f531b26e01a7d61f18b50659890a5e07b1
```

-	Total Virtual Size: 985.4 MB (985443965 bytes)
-	Total v2 Content-Length: 378.8 MB (378812018 bytes)

### Layers (5)

#### `0f505133a3b99502340358a20826acfa5d43b6ef7e2b64ad5ddfc8f0fac5c855`

```dockerfile
ADD file:113653a4a76ebce4343758a16fbbb22ccc40b4ed9285eb62de9775d94b110a31 in /
```

-	Created: Fri, 04 Dec 2015 19:29:17 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 116.7 MB (116711866 bytes)
-	v2 Blob: `sha256:db77e04b88e12d6724c93949d09dce661a66719fe0c819b5f66a5332037dd328`
-	v2 Content-Length: 51.7 MB (51657474 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 19:48:45 GMT

#### `20b3d0655ab649aa47ab2a073239b980590f99945f78e562173de756ad63d3da`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Fri, 04 Dec 2015 19:29:42 GMT
-	Parent Layer: `0f505133a3b99502340358a20826acfa5d43b6ef7e2b64ad5ddfc8f0fac5c855`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `7d0fa6f23d25a8eda5baf81f34605892e3d0cb3993b29ea7fd1e34d4f0fe3c8c`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:36:16 GMT
-	Parent Layer: `20b3d0655ab649aa47ab2a073239b980590f99945f78e562173de756ad63d3da`
-	Docker Version: 1.8.3
-	Virtual Size: 48.8 MB (48753154 bytes)
-	v2 Blob: `sha256:eba085212fbf6e68c7eff37a948f7042f1fb2c870fedcba765b8cb965ab51c81`
-	v2 Content-Length: 20.4 MB (20351720 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 20:01:55 GMT

#### `6de76ee12a14900325ad14e01f77abcd935801a1b862e0ddb1c6813e47bfed11`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:36:42 GMT
-	Parent Layer: `7d0fa6f23d25a8eda5baf81f34605892e3d0cb3993b29ea7fd1e34d4f0fe3c8c`
-	Docker Version: 1.8.3
-	Virtual Size: 128.2 MB (128179041 bytes)
-	v2 Blob: `sha256:9b9f23286c2453295057de9b1248ccf80b54ca95ccde49f1b095e983b9e9b7ff`
-	v2 Content-Length: 44.6 MB (44628020 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 20:03:30 GMT

#### `2659d243ea1578ab0c9c5b83c4eda48e40c97f743bf784b17f9810b1dd11f517`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:38:05 GMT
-	Parent Layer: `6de76ee12a14900325ad14e01f77abcd935801a1b862e0ddb1c6813e47bfed11`
-	Docker Version: 1.8.3
-	Virtual Size: 691.8 MB (691799904 bytes)
-	v2 Blob: `sha256:fe546de06897acefe0b0671957fd922a61969c5ea96c964022b767629b39f554`
-	v2 Content-Length: 262.2 MB (262174772 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 20:05:59 GMT

## `buildpack-deps:stretch-curl`

```console
$ docker pull library/buildpack-deps@sha256:293a48e73542daa948a3cff362ad79909e340f83fc243e252c05fea1cd65a054
```

-	Total Virtual Size: 165.5 MB (165544216 bytes)
-	Total v2 Content-Length: 72.0 MB (72017000 bytes)

### Layers (3)

#### `46930237d8f90379d9d8b3afa7cbd3635a3167261a9627ee608612c831b8e8df`

```dockerfile
ADD file:2740754650fb9536cc1bb7abc6cb701ae7d79cadacd0fd54a5db81b8e343f435 in /
```

-	Created: Fri, 04 Dec 2015 19:30:36 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 116.8 MB (116773740 bytes)
-	v2 Blob: `sha256:980dfbf5d5e5364b44e6e99abe5d46622f205eeb58add2a901685840d6c8685b`
-	v2 Content-Length: 51.6 MB (51647367 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 19:52:30 GMT

#### `35b0af67478101615c92763442551dc1171c58e8fadb961b0a4cd3aa4d2d2b0d`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Fri, 04 Dec 2015 19:30:39 GMT
-	Parent Layer: `46930237d8f90379d9d8b3afa7cbd3635a3167261a9627ee608612c831b8e8df`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `1f3b1fb0495abebda5682a9b88dd3c7793a63e62c73738bd4870f0620117a71f`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:38:41 GMT
-	Parent Layer: `35b0af67478101615c92763442551dc1171c58e8fadb961b0a4cd3aa4d2d2b0d`
-	Docker Version: 1.8.3
-	Virtual Size: 48.8 MB (48770476 bytes)
-	v2 Blob: `sha256:ee965fc7a113748340e6b3c29bee6eafcad1074d791c3f4f18e4808e25db4c79`
-	v2 Content-Length: 20.4 MB (20369601 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 20:08:20 GMT

## `buildpack-deps:stretch-scm`

```console
$ docker pull library/buildpack-deps@sha256:a0abaa516ea393a24f6748d07c5e01a5765d4aae67d1306a25b5b1aa119d1d1a
```

-	Total Virtual Size: 293.4 MB (293426072 bytes)
-	Total v2 Content-Length: 116.6 MB (116558966 bytes)

### Layers (4)

#### `46930237d8f90379d9d8b3afa7cbd3635a3167261a9627ee608612c831b8e8df`

```dockerfile
ADD file:2740754650fb9536cc1bb7abc6cb701ae7d79cadacd0fd54a5db81b8e343f435 in /
```

-	Created: Fri, 04 Dec 2015 19:30:36 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 116.8 MB (116773740 bytes)
-	v2 Blob: `sha256:980dfbf5d5e5364b44e6e99abe5d46622f205eeb58add2a901685840d6c8685b`
-	v2 Content-Length: 51.6 MB (51647367 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 19:52:30 GMT

#### `35b0af67478101615c92763442551dc1171c58e8fadb961b0a4cd3aa4d2d2b0d`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Fri, 04 Dec 2015 19:30:39 GMT
-	Parent Layer: `46930237d8f90379d9d8b3afa7cbd3635a3167261a9627ee608612c831b8e8df`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `1f3b1fb0495abebda5682a9b88dd3c7793a63e62c73738bd4870f0620117a71f`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:38:41 GMT
-	Parent Layer: `35b0af67478101615c92763442551dc1171c58e8fadb961b0a4cd3aa4d2d2b0d`
-	Docker Version: 1.8.3
-	Virtual Size: 48.8 MB (48770476 bytes)
-	v2 Blob: `sha256:ee965fc7a113748340e6b3c29bee6eafcad1074d791c3f4f18e4808e25db4c79`
-	v2 Content-Length: 20.4 MB (20369601 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 20:08:20 GMT

#### `826a47cdf63b58a2bdb95fd272b2c79c1a6ec9d2a27c8a78dc6787e68ee7569b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:39:09 GMT
-	Parent Layer: `1f3b1fb0495abebda5682a9b88dd3c7793a63e62c73738bd4870f0620117a71f`
-	Docker Version: 1.8.3
-	Virtual Size: 127.9 MB (127881856 bytes)
-	v2 Blob: `sha256:9e09f8a93c40b3f71bbe1f80220f5d6537fbee7c202a0d0bffc15bda1744bbaf`
-	v2 Content-Length: 44.5 MB (44541966 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 20:09:54 GMT

## `buildpack-deps:stretch`

```console
$ docker pull library/buildpack-deps@sha256:3d08baec46b1cc6db3936bdafbf1b7cd8eaa42b1aeae3cbb9fab896305577d1c
```

-	Total Virtual Size: 993.0 MB (992978204 bytes)
-	Total v2 Content-Length: 387.5 MB (387503964 bytes)

### Layers (5)

#### `46930237d8f90379d9d8b3afa7cbd3635a3167261a9627ee608612c831b8e8df`

```dockerfile
ADD file:2740754650fb9536cc1bb7abc6cb701ae7d79cadacd0fd54a5db81b8e343f435 in /
```

-	Created: Fri, 04 Dec 2015 19:30:36 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 116.8 MB (116773740 bytes)
-	v2 Blob: `sha256:980dfbf5d5e5364b44e6e99abe5d46622f205eeb58add2a901685840d6c8685b`
-	v2 Content-Length: 51.6 MB (51647367 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 19:52:30 GMT

#### `35b0af67478101615c92763442551dc1171c58e8fadb961b0a4cd3aa4d2d2b0d`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Fri, 04 Dec 2015 19:30:39 GMT
-	Parent Layer: `46930237d8f90379d9d8b3afa7cbd3635a3167261a9627ee608612c831b8e8df`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `1f3b1fb0495abebda5682a9b88dd3c7793a63e62c73738bd4870f0620117a71f`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:38:41 GMT
-	Parent Layer: `35b0af67478101615c92763442551dc1171c58e8fadb961b0a4cd3aa4d2d2b0d`
-	Docker Version: 1.8.3
-	Virtual Size: 48.8 MB (48770476 bytes)
-	v2 Blob: `sha256:ee965fc7a113748340e6b3c29bee6eafcad1074d791c3f4f18e4808e25db4c79`
-	v2 Content-Length: 20.4 MB (20369601 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 20:08:20 GMT

#### `826a47cdf63b58a2bdb95fd272b2c79c1a6ec9d2a27c8a78dc6787e68ee7569b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:39:09 GMT
-	Parent Layer: `1f3b1fb0495abebda5682a9b88dd3c7793a63e62c73738bd4870f0620117a71f`
-	Docker Version: 1.8.3
-	Virtual Size: 127.9 MB (127881856 bytes)
-	v2 Blob: `sha256:9e09f8a93c40b3f71bbe1f80220f5d6537fbee7c202a0d0bffc15bda1744bbaf`
-	v2 Content-Length: 44.5 MB (44541966 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 20:09:54 GMT

#### `500318bf55063ce8ca5fa81447087ac2b1f806cc09d6622e01452fb461f08547`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:41:37 GMT
-	Parent Layer: `826a47cdf63b58a2bdb95fd272b2c79c1a6ec9d2a27c8a78dc6787e68ee7569b`
-	Docker Version: 1.8.3
-	Virtual Size: 699.6 MB (699552132 bytes)
-	v2 Blob: `sha256:9ab5c88ec62d44cb13138afb669a81ac247b97be4461eba99ff8703dab40162a`
-	v2 Content-Length: 270.9 MB (270944998 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 20:12:24 GMT

## `buildpack-deps:trusty-curl`

```console
$ docker pull library/buildpack-deps@sha256:6e194eee30b823c4097a617a5fcb4fec50296a18fbebcd0b6550f5e798b6c8b9
```

-	Total Virtual Size: 199.6 MB (199598650 bytes)
-	Total v2 Content-Length: 70.3 MB (70343283 bytes)

### Layers (5)

#### `2332d8973c9393d58c03693bb4d8ec8bd853bafda3b897d48b391a1d0ba9ffb0`

```dockerfile
ADD file:531ac3e55db4293b8f2a989e5e19d1123fba9f7bf2803357d754a023c98e6ffb in /
```

-	Created: Tue, 10 Nov 2015 00:35:00 GMT
-	Docker Version: 1.9.0
-	Virtual Size: 187.7 MB (187722872 bytes)
-	v2 Blob: `sha256:863735b9fd15b7617298df56e767c6057c4439df896d1d4b0e5e09fa50377496`
-	v2 Content-Length: 65.7 MB (65670599 bytes)
-	v2 Last-Modified: Tue, 10 Nov 2015 01:45:40 GMT

#### `ea358092da773eff1664fd484edeffb0011f26b4f1dd34ad11b73db57c91d8ae`

```dockerfile
RUN echo '#!/bin/sh' > /usr/sbin/policy-rc.d \
	&& echo 'exit 101' >> /usr/sbin/policy-rc.d \
	&& chmod +x /usr/sbin/policy-rc.d \
		&& dpkg-divert --local --rename --add /sbin/initctl \
	&& cp -a /usr/sbin/policy-rc.d /sbin/initctl \
	&& sed -i 's/^exit.*/exit 0/' /sbin/initctl \
		&& echo 'force-unsafe-io' > /etc/dpkg/dpkg.cfg.d/docker-apt-speedup \
		&& echo 'DPkg::Post-Invoke { "rm -f /var/cache/apt/archives/*.deb /var/cache/apt/archives/partial/*.deb /var/cache/apt/*.bin || true"; };' > /etc/apt/apt.conf.d/docker-clean \
	&& echo 'APT::Update::Post-Invoke { "rm -f /var/cache/apt/archives/*.deb /var/cache/apt/archives/partial/*.deb /var/cache/apt/*.bin || true"; };' >> /etc/apt/apt.conf.d/docker-clean \
	&& echo 'Dir::Cache::pkgcache ""; Dir::Cache::srcpkgcache "";' >> /etc/apt/apt.conf.d/docker-clean \
		&& echo 'Acquire::Languages "none";' > /etc/apt/apt.conf.d/docker-no-languages \
		&& echo 'Acquire::GzipIndexes "true"; Acquire::CompressionTypes::Order:: "gz";' > /etc/apt/apt.conf.d/docker-gzip-indexes
```

-	Created: Tue, 10 Nov 2015 00:35:05 GMT
-	Parent Layer: `2332d8973c9393d58c03693bb4d8ec8bd853bafda3b897d48b391a1d0ba9ffb0`
-	Docker Version: 1.9.0
-	Virtual Size: 194.5 KB (194533 bytes)
-	v2 Blob: `sha256:4fbaa2f403dffcc9050448f94c0e0b32d1a12b74379738a53a69e686cce4da7e`
-	v2 Content-Length: 71.5 KB (71477 bytes)
-	v2 Last-Modified: Tue, 10 Nov 2015 18:02:04 GMT

#### `a467a7c6794fd7ebd5bd0e2dcb83a656ac8302e549c4a2cc29c524aea5c5623b`

```dockerfile
RUN sed -i 's/^#\s*\(deb.*universe\)$/\1/g' /etc/apt/sources.list
```

-	Created: Tue, 10 Nov 2015 00:35:06 GMT
-	Parent Layer: `ea358092da773eff1664fd484edeffb0011f26b4f1dd34ad11b73db57c91d8ae`
-	Docker Version: 1.9.0
-	Virtual Size: 1.9 KB (1895 bytes)
-	v2 Blob: `sha256:44be94a95984bb47dc3a193f59bf8c04d5e877160b745b119278f38753a6f58f`
-	v2 Content-Length: 681.0 B
-	v2 Last-Modified: Tue, 10 Nov 2015 18:02:01 GMT

#### `ca4d7b1b9a51f72ff4da652d96943f657b4898889924ac3dae5df958dba0dc4a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 10 Nov 2015 00:35:07 GMT
-	Parent Layer: `a467a7c6794fd7ebd5bd0e2dcb83a656ac8302e549c4a2cc29c524aea5c5623b`
-	Docker Version: 1.9.0
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0faf2b60014515cfd3bdd5ca165eaec2056a688bf8c3015775db6e58d1eb7732`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 10 Nov 2015 17:40:52 GMT
-	Parent Layer: `ca4d7b1b9a51f72ff4da652d96943f657b4898889924ac3dae5df958dba0dc4a`
-	Docker Version: 1.9.0
-	Virtual Size: 11.7 MB (11679350 bytes)
-	v2 Blob: `sha256:1884c435d7da4dacaf8d70eee21e0589107db61bce41cf809a6493562559c1bf`
-	v2 Content-Length: 4.6 MB (4600494 bytes)
-	v2 Last-Modified: Tue, 10 Nov 2015 18:24:14 GMT

## `buildpack-deps:trusty-scm`

```console
$ docker pull library/buildpack-deps@sha256:2884d8a8f24db8f3c47c6e652c54a026c6bbf43dda0b832413fb2e7e47133d79
```

-	Total Virtual Size: 279.3 MB (279288392 bytes)
-	Total v2 Content-Length: 99.2 MB (99194206 bytes)

### Layers (6)

#### `2332d8973c9393d58c03693bb4d8ec8bd853bafda3b897d48b391a1d0ba9ffb0`

```dockerfile
ADD file:531ac3e55db4293b8f2a989e5e19d1123fba9f7bf2803357d754a023c98e6ffb in /
```

-	Created: Tue, 10 Nov 2015 00:35:00 GMT
-	Docker Version: 1.9.0
-	Virtual Size: 187.7 MB (187722872 bytes)
-	v2 Blob: `sha256:863735b9fd15b7617298df56e767c6057c4439df896d1d4b0e5e09fa50377496`
-	v2 Content-Length: 65.7 MB (65670599 bytes)
-	v2 Last-Modified: Tue, 10 Nov 2015 01:45:40 GMT

#### `ea358092da773eff1664fd484edeffb0011f26b4f1dd34ad11b73db57c91d8ae`

```dockerfile
RUN echo '#!/bin/sh' > /usr/sbin/policy-rc.d \
	&& echo 'exit 101' >> /usr/sbin/policy-rc.d \
	&& chmod +x /usr/sbin/policy-rc.d \
		&& dpkg-divert --local --rename --add /sbin/initctl \
	&& cp -a /usr/sbin/policy-rc.d /sbin/initctl \
	&& sed -i 's/^exit.*/exit 0/' /sbin/initctl \
		&& echo 'force-unsafe-io' > /etc/dpkg/dpkg.cfg.d/docker-apt-speedup \
		&& echo 'DPkg::Post-Invoke { "rm -f /var/cache/apt/archives/*.deb /var/cache/apt/archives/partial/*.deb /var/cache/apt/*.bin || true"; };' > /etc/apt/apt.conf.d/docker-clean \
	&& echo 'APT::Update::Post-Invoke { "rm -f /var/cache/apt/archives/*.deb /var/cache/apt/archives/partial/*.deb /var/cache/apt/*.bin || true"; };' >> /etc/apt/apt.conf.d/docker-clean \
	&& echo 'Dir::Cache::pkgcache ""; Dir::Cache::srcpkgcache "";' >> /etc/apt/apt.conf.d/docker-clean \
		&& echo 'Acquire::Languages "none";' > /etc/apt/apt.conf.d/docker-no-languages \
		&& echo 'Acquire::GzipIndexes "true"; Acquire::CompressionTypes::Order:: "gz";' > /etc/apt/apt.conf.d/docker-gzip-indexes
```

-	Created: Tue, 10 Nov 2015 00:35:05 GMT
-	Parent Layer: `2332d8973c9393d58c03693bb4d8ec8bd853bafda3b897d48b391a1d0ba9ffb0`
-	Docker Version: 1.9.0
-	Virtual Size: 194.5 KB (194533 bytes)
-	v2 Blob: `sha256:4fbaa2f403dffcc9050448f94c0e0b32d1a12b74379738a53a69e686cce4da7e`
-	v2 Content-Length: 71.5 KB (71477 bytes)
-	v2 Last-Modified: Tue, 10 Nov 2015 18:02:04 GMT

#### `a467a7c6794fd7ebd5bd0e2dcb83a656ac8302e549c4a2cc29c524aea5c5623b`

```dockerfile
RUN sed -i 's/^#\s*\(deb.*universe\)$/\1/g' /etc/apt/sources.list
```

-	Created: Tue, 10 Nov 2015 00:35:06 GMT
-	Parent Layer: `ea358092da773eff1664fd484edeffb0011f26b4f1dd34ad11b73db57c91d8ae`
-	Docker Version: 1.9.0
-	Virtual Size: 1.9 KB (1895 bytes)
-	v2 Blob: `sha256:44be94a95984bb47dc3a193f59bf8c04d5e877160b745b119278f38753a6f58f`
-	v2 Content-Length: 681.0 B
-	v2 Last-Modified: Tue, 10 Nov 2015 18:02:01 GMT

#### `ca4d7b1b9a51f72ff4da652d96943f657b4898889924ac3dae5df958dba0dc4a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 10 Nov 2015 00:35:07 GMT
-	Parent Layer: `a467a7c6794fd7ebd5bd0e2dcb83a656ac8302e549c4a2cc29c524aea5c5623b`
-	Docker Version: 1.9.0
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0faf2b60014515cfd3bdd5ca165eaec2056a688bf8c3015775db6e58d1eb7732`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 10 Nov 2015 17:40:52 GMT
-	Parent Layer: `ca4d7b1b9a51f72ff4da652d96943f657b4898889924ac3dae5df958dba0dc4a`
-	Docker Version: 1.9.0
-	Virtual Size: 11.7 MB (11679350 bytes)
-	v2 Blob: `sha256:1884c435d7da4dacaf8d70eee21e0589107db61bce41cf809a6493562559c1bf`
-	v2 Content-Length: 4.6 MB (4600494 bytes)
-	v2 Last-Modified: Tue, 10 Nov 2015 18:24:14 GMT

#### `ce6f2e6411a4eaeb00a81f2e1e4faba2e51b4510c5294497ff16492b50e48395`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Wed, 25 Nov 2015 17:00:35 GMT
-	Parent Layer: `0faf2b60014515cfd3bdd5ca165eaec2056a688bf8c3015775db6e58d1eb7732`
-	Docker Version: 1.8.3
-	Virtual Size: 79.7 MB (79689742 bytes)
-	v2 Blob: `sha256:93841bea868e2431e845c87854dfc711a1edbc76c37b0ff70b7599283fb358c5`
-	v2 Content-Length: 28.9 MB (28850923 bytes)
-	v2 Last-Modified: Wed, 25 Nov 2015 18:15:45 GMT

## `buildpack-deps:trusty`

```console
$ docker pull library/buildpack-deps@sha256:9f54744e60f9a29a42abc74afefa5d2699cd6c3719b89a32d806c4a32fef51db
```

-	Total Virtual Size: 533.7 MB (533683660 bytes)
-	Total v2 Content-Length: 195.6 MB (195571376 bytes)

### Layers (7)

#### `2332d8973c9393d58c03693bb4d8ec8bd853bafda3b897d48b391a1d0ba9ffb0`

```dockerfile
ADD file:531ac3e55db4293b8f2a989e5e19d1123fba9f7bf2803357d754a023c98e6ffb in /
```

-	Created: Tue, 10 Nov 2015 00:35:00 GMT
-	Docker Version: 1.9.0
-	Virtual Size: 187.7 MB (187722872 bytes)
-	v2 Blob: `sha256:863735b9fd15b7617298df56e767c6057c4439df896d1d4b0e5e09fa50377496`
-	v2 Content-Length: 65.7 MB (65670599 bytes)
-	v2 Last-Modified: Tue, 10 Nov 2015 01:45:40 GMT

#### `ea358092da773eff1664fd484edeffb0011f26b4f1dd34ad11b73db57c91d8ae`

```dockerfile
RUN echo '#!/bin/sh' > /usr/sbin/policy-rc.d \
	&& echo 'exit 101' >> /usr/sbin/policy-rc.d \
	&& chmod +x /usr/sbin/policy-rc.d \
		&& dpkg-divert --local --rename --add /sbin/initctl \
	&& cp -a /usr/sbin/policy-rc.d /sbin/initctl \
	&& sed -i 's/^exit.*/exit 0/' /sbin/initctl \
		&& echo 'force-unsafe-io' > /etc/dpkg/dpkg.cfg.d/docker-apt-speedup \
		&& echo 'DPkg::Post-Invoke { "rm -f /var/cache/apt/archives/*.deb /var/cache/apt/archives/partial/*.deb /var/cache/apt/*.bin || true"; };' > /etc/apt/apt.conf.d/docker-clean \
	&& echo 'APT::Update::Post-Invoke { "rm -f /var/cache/apt/archives/*.deb /var/cache/apt/archives/partial/*.deb /var/cache/apt/*.bin || true"; };' >> /etc/apt/apt.conf.d/docker-clean \
	&& echo 'Dir::Cache::pkgcache ""; Dir::Cache::srcpkgcache "";' >> /etc/apt/apt.conf.d/docker-clean \
		&& echo 'Acquire::Languages "none";' > /etc/apt/apt.conf.d/docker-no-languages \
		&& echo 'Acquire::GzipIndexes "true"; Acquire::CompressionTypes::Order:: "gz";' > /etc/apt/apt.conf.d/docker-gzip-indexes
```

-	Created: Tue, 10 Nov 2015 00:35:05 GMT
-	Parent Layer: `2332d8973c9393d58c03693bb4d8ec8bd853bafda3b897d48b391a1d0ba9ffb0`
-	Docker Version: 1.9.0
-	Virtual Size: 194.5 KB (194533 bytes)
-	v2 Blob: `sha256:4fbaa2f403dffcc9050448f94c0e0b32d1a12b74379738a53a69e686cce4da7e`
-	v2 Content-Length: 71.5 KB (71477 bytes)
-	v2 Last-Modified: Tue, 10 Nov 2015 18:02:04 GMT

#### `a467a7c6794fd7ebd5bd0e2dcb83a656ac8302e549c4a2cc29c524aea5c5623b`

```dockerfile
RUN sed -i 's/^#\s*\(deb.*universe\)$/\1/g' /etc/apt/sources.list
```

-	Created: Tue, 10 Nov 2015 00:35:06 GMT
-	Parent Layer: `ea358092da773eff1664fd484edeffb0011f26b4f1dd34ad11b73db57c91d8ae`
-	Docker Version: 1.9.0
-	Virtual Size: 1.9 KB (1895 bytes)
-	v2 Blob: `sha256:44be94a95984bb47dc3a193f59bf8c04d5e877160b745b119278f38753a6f58f`
-	v2 Content-Length: 681.0 B
-	v2 Last-Modified: Tue, 10 Nov 2015 18:02:01 GMT

#### `ca4d7b1b9a51f72ff4da652d96943f657b4898889924ac3dae5df958dba0dc4a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Tue, 10 Nov 2015 00:35:07 GMT
-	Parent Layer: `a467a7c6794fd7ebd5bd0e2dcb83a656ac8302e549c4a2cc29c524aea5c5623b`
-	Docker Version: 1.9.0
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `0faf2b60014515cfd3bdd5ca165eaec2056a688bf8c3015775db6e58d1eb7732`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Tue, 10 Nov 2015 17:40:52 GMT
-	Parent Layer: `ca4d7b1b9a51f72ff4da652d96943f657b4898889924ac3dae5df958dba0dc4a`
-	Docker Version: 1.9.0
-	Virtual Size: 11.7 MB (11679350 bytes)
-	v2 Blob: `sha256:1884c435d7da4dacaf8d70eee21e0589107db61bce41cf809a6493562559c1bf`
-	v2 Content-Length: 4.6 MB (4600494 bytes)
-	v2 Last-Modified: Tue, 10 Nov 2015 18:24:14 GMT

#### `ce6f2e6411a4eaeb00a81f2e1e4faba2e51b4510c5294497ff16492b50e48395`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Wed, 25 Nov 2015 17:00:35 GMT
-	Parent Layer: `0faf2b60014515cfd3bdd5ca165eaec2056a688bf8c3015775db6e58d1eb7732`
-	Docker Version: 1.8.3
-	Virtual Size: 79.7 MB (79689742 bytes)
-	v2 Blob: `sha256:93841bea868e2431e845c87854dfc711a1edbc76c37b0ff70b7599283fb358c5`
-	v2 Content-Length: 28.9 MB (28850923 bytes)
-	v2 Last-Modified: Wed, 25 Nov 2015 18:15:45 GMT

#### `69725df6cb1f17109ee454eafecd700d021d2c3c261e1d5d4491fd04a71540d9`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Wed, 25 Nov 2015 17:02:36 GMT
-	Parent Layer: `ce6f2e6411a4eaeb00a81f2e1e4faba2e51b4510c5294497ff16492b50e48395`
-	Docker Version: 1.8.3
-	Virtual Size: 254.4 MB (254395268 bytes)
-	v2 Blob: `sha256:1e978e043fa452d575955c98923422b454245f67dd8f379e8f6382ce3aedf340`
-	v2 Content-Length: 96.4 MB (96377170 bytes)
-	v2 Last-Modified: Wed, 25 Nov 2015 18:17:00 GMT

## `buildpack-deps:vivid-curl`

```console
$ docker pull library/buildpack-deps@sha256:e273eb579d5059a8dadfa43de9c1961ca39cd272c4c7874ed06939628d67847f
```

-	Total Virtual Size: 147.4 MB (147420833 bytes)
-	Total v2 Content-Length: 56.2 MB (56172062 bytes)

### Layers (5)

#### `f951648fc00de32c256043a6cfc0c16545547aa696318361f5e72709d558135e`

```dockerfile
ADD file:57de4a7626127f55f1d0b14e6e4d3e7e6536731dbe2c3c4dda2cbf3987510364 in /
```

-	Created: Fri, 20 Nov 2015 04:57:21 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 131.3 MB (131297850 bytes)
-	v2 Blob: `sha256:21162f7e79a5ccca37a7b5aaa2693ce45a47406955d4b746f56430139a1b7327`
-	v2 Content-Length: 49.3 MB (49332408 bytes)
-	v2 Last-Modified: Fri, 20 Nov 2015 05:02:59 GMT

#### `213b4a4f666de4dad35ac1545b6d7eb9086a5f949921532c292869707e7adb30`

```dockerfile
RUN echo '#!/bin/sh' > /usr/sbin/policy-rc.d \
	&& echo 'exit 101' >> /usr/sbin/policy-rc.d \
	&& chmod +x /usr/sbin/policy-rc.d \
		&& dpkg-divert --local --rename --add /sbin/initctl \
	&& cp -a /usr/sbin/policy-rc.d /sbin/initctl \
	&& sed -i 's/^exit.*/exit 0/' /sbin/initctl \
		&& echo 'force-unsafe-io' > /etc/dpkg/dpkg.cfg.d/docker-apt-speedup \
		&& echo 'DPkg::Post-Invoke { "rm -f /var/cache/apt/archives/*.deb /var/cache/apt/archives/partial/*.deb /var/cache/apt/*.bin || true"; };' > /etc/apt/apt.conf.d/docker-clean \
	&& echo 'APT::Update::Post-Invoke { "rm -f /var/cache/apt/archives/*.deb /var/cache/apt/archives/partial/*.deb /var/cache/apt/*.bin || true"; };' >> /etc/apt/apt.conf.d/docker-clean \
	&& echo 'Dir::Cache::pkgcache ""; Dir::Cache::srcpkgcache "";' >> /etc/apt/apt.conf.d/docker-clean \
		&& echo 'Acquire::Languages "none";' > /etc/apt/apt.conf.d/docker-no-languages \
		&& echo 'Acquire::GzipIndexes "true"; Acquire::CompressionTypes::Order:: "gz";' > /etc/apt/apt.conf.d/docker-gzip-indexes
```

-	Created: Fri, 20 Nov 2015 04:57:24 GMT
-	Parent Layer: `f951648fc00de32c256043a6cfc0c16545547aa696318361f5e72709d558135e`
-	Docker Version: 1.8.3
-	Virtual Size: 701.0 B
-	v2 Blob: `sha256:8e234ff2f9273864f919a11ef87f3e47fd7592038c1d4754916045aa9eb21651`
-	v2 Content-Length: 759.0 B
-	v2 Last-Modified: Fri, 20 Nov 2015 05:02:25 GMT

#### `d9b1b9e57d8e7971041d2753e78f6931a06053bd4633a6567b352c3a30e674b6`

```dockerfile
RUN sed -i 's/^#\s*\(deb.*universe\)$/\1/g' /etc/apt/sources.list
```

-	Created: Fri, 20 Nov 2015 04:57:26 GMT
-	Parent Layer: `213b4a4f666de4dad35ac1545b6d7eb9086a5f949921532c292869707e7adb30`
-	Docker Version: 1.8.3
-	Virtual Size: 1.9 KB (1879 bytes)
-	v2 Blob: `sha256:a71b7b742fee2c204426d9a193a56f3ea223eef84810b85c1840811663ca5dcb`
-	v2 Content-Length: 677.0 B
-	v2 Last-Modified: Fri, 20 Nov 2015 05:02:20 GMT

#### `db672630245b8058c9886e94edf869f951289bdbb6f088f458681cf4636a162a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Fri, 20 Nov 2015 04:57:26 GMT
-	Parent Layer: `d9b1b9e57d8e7971041d2753e78f6931a06053bd4633a6567b352c3a30e674b6`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `401596022d7ae8c775e489219fc94b34a3dbbffaddc0f73a6a324ef485ce249b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 20 Nov 2015 05:12:22 GMT
-	Parent Layer: `db672630245b8058c9886e94edf869f951289bdbb6f088f458681cf4636a162a`
-	Docker Version: 1.8.3
-	Virtual Size: 16.1 MB (16120403 bytes)
-	v2 Blob: `sha256:90c6cb01029bb11efaa4e5175e6a3fd48274bc8dbcc51de67108a94cef413764`
-	v2 Content-Length: 6.8 MB (6838186 bytes)
-	v2 Last-Modified: Fri, 20 Nov 2015 05:41:32 GMT

## `buildpack-deps:vivid-scm`

```console
$ docker pull library/buildpack-deps@sha256:3556ee105ad6c66af90e7e77e3eeb671bc2eddf763a631e38e5d65dba71db599
```

-	Total Virtual Size: 259.5 MB (259543248 bytes)
-	Total v2 Content-Length: 93.7 MB (93655875 bytes)

### Layers (6)

#### `f951648fc00de32c256043a6cfc0c16545547aa696318361f5e72709d558135e`

```dockerfile
ADD file:57de4a7626127f55f1d0b14e6e4d3e7e6536731dbe2c3c4dda2cbf3987510364 in /
```

-	Created: Fri, 20 Nov 2015 04:57:21 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 131.3 MB (131297850 bytes)
-	v2 Blob: `sha256:21162f7e79a5ccca37a7b5aaa2693ce45a47406955d4b746f56430139a1b7327`
-	v2 Content-Length: 49.3 MB (49332408 bytes)
-	v2 Last-Modified: Fri, 20 Nov 2015 05:02:59 GMT

#### `213b4a4f666de4dad35ac1545b6d7eb9086a5f949921532c292869707e7adb30`

```dockerfile
RUN echo '#!/bin/sh' > /usr/sbin/policy-rc.d \
	&& echo 'exit 101' >> /usr/sbin/policy-rc.d \
	&& chmod +x /usr/sbin/policy-rc.d \
		&& dpkg-divert --local --rename --add /sbin/initctl \
	&& cp -a /usr/sbin/policy-rc.d /sbin/initctl \
	&& sed -i 's/^exit.*/exit 0/' /sbin/initctl \
		&& echo 'force-unsafe-io' > /etc/dpkg/dpkg.cfg.d/docker-apt-speedup \
		&& echo 'DPkg::Post-Invoke { "rm -f /var/cache/apt/archives/*.deb /var/cache/apt/archives/partial/*.deb /var/cache/apt/*.bin || true"; };' > /etc/apt/apt.conf.d/docker-clean \
	&& echo 'APT::Update::Post-Invoke { "rm -f /var/cache/apt/archives/*.deb /var/cache/apt/archives/partial/*.deb /var/cache/apt/*.bin || true"; };' >> /etc/apt/apt.conf.d/docker-clean \
	&& echo 'Dir::Cache::pkgcache ""; Dir::Cache::srcpkgcache "";' >> /etc/apt/apt.conf.d/docker-clean \
		&& echo 'Acquire::Languages "none";' > /etc/apt/apt.conf.d/docker-no-languages \
		&& echo 'Acquire::GzipIndexes "true"; Acquire::CompressionTypes::Order:: "gz";' > /etc/apt/apt.conf.d/docker-gzip-indexes
```

-	Created: Fri, 20 Nov 2015 04:57:24 GMT
-	Parent Layer: `f951648fc00de32c256043a6cfc0c16545547aa696318361f5e72709d558135e`
-	Docker Version: 1.8.3
-	Virtual Size: 701.0 B
-	v2 Blob: `sha256:8e234ff2f9273864f919a11ef87f3e47fd7592038c1d4754916045aa9eb21651`
-	v2 Content-Length: 759.0 B
-	v2 Last-Modified: Fri, 20 Nov 2015 05:02:25 GMT

#### `d9b1b9e57d8e7971041d2753e78f6931a06053bd4633a6567b352c3a30e674b6`

```dockerfile
RUN sed -i 's/^#\s*\(deb.*universe\)$/\1/g' /etc/apt/sources.list
```

-	Created: Fri, 20 Nov 2015 04:57:26 GMT
-	Parent Layer: `213b4a4f666de4dad35ac1545b6d7eb9086a5f949921532c292869707e7adb30`
-	Docker Version: 1.8.3
-	Virtual Size: 1.9 KB (1879 bytes)
-	v2 Blob: `sha256:a71b7b742fee2c204426d9a193a56f3ea223eef84810b85c1840811663ca5dcb`
-	v2 Content-Length: 677.0 B
-	v2 Last-Modified: Fri, 20 Nov 2015 05:02:20 GMT

#### `db672630245b8058c9886e94edf869f951289bdbb6f088f458681cf4636a162a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Fri, 20 Nov 2015 04:57:26 GMT
-	Parent Layer: `d9b1b9e57d8e7971041d2753e78f6931a06053bd4633a6567b352c3a30e674b6`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `401596022d7ae8c775e489219fc94b34a3dbbffaddc0f73a6a324ef485ce249b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 20 Nov 2015 05:12:22 GMT
-	Parent Layer: `db672630245b8058c9886e94edf869f951289bdbb6f088f458681cf4636a162a`
-	Docker Version: 1.8.3
-	Virtual Size: 16.1 MB (16120403 bytes)
-	v2 Blob: `sha256:90c6cb01029bb11efaa4e5175e6a3fd48274bc8dbcc51de67108a94cef413764`
-	v2 Content-Length: 6.8 MB (6838186 bytes)
-	v2 Last-Modified: Fri, 20 Nov 2015 05:41:32 GMT

#### `f1115ccafdf3fd2947ee00f0ae1571999992b328bfb6a45289c751f708b59284`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Wed, 25 Nov 2015 17:04:02 GMT
-	Parent Layer: `401596022d7ae8c775e489219fc94b34a3dbbffaddc0f73a6a324ef485ce249b`
-	Docker Version: 1.8.3
-	Virtual Size: 112.1 MB (112122415 bytes)
-	v2 Blob: `sha256:4f77f03ad84164269a4dd1c5def3c1427d87961d81d6a4a0d8fce47a8a2040fa`
-	v2 Content-Length: 37.5 MB (37483813 bytes)
-	v2 Last-Modified: Wed, 25 Nov 2015 18:18:28 GMT

## `buildpack-deps:vivid`

```console
$ docker pull library/buildpack-deps@sha256:34d8df79c5d4794369672819e4149bfe171e0e31c17ca0e1474b0849703eb5ac
```

-	Total Virtual Size: 600.0 MB (600039791 bytes)
-	Total v2 Content-Length: 220.5 MB (220495936 bytes)

### Layers (7)

#### `f951648fc00de32c256043a6cfc0c16545547aa696318361f5e72709d558135e`

```dockerfile
ADD file:57de4a7626127f55f1d0b14e6e4d3e7e6536731dbe2c3c4dda2cbf3987510364 in /
```

-	Created: Fri, 20 Nov 2015 04:57:21 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 131.3 MB (131297850 bytes)
-	v2 Blob: `sha256:21162f7e79a5ccca37a7b5aaa2693ce45a47406955d4b746f56430139a1b7327`
-	v2 Content-Length: 49.3 MB (49332408 bytes)
-	v2 Last-Modified: Fri, 20 Nov 2015 05:02:59 GMT

#### `213b4a4f666de4dad35ac1545b6d7eb9086a5f949921532c292869707e7adb30`

```dockerfile
RUN echo '#!/bin/sh' > /usr/sbin/policy-rc.d \
	&& echo 'exit 101' >> /usr/sbin/policy-rc.d \
	&& chmod +x /usr/sbin/policy-rc.d \
		&& dpkg-divert --local --rename --add /sbin/initctl \
	&& cp -a /usr/sbin/policy-rc.d /sbin/initctl \
	&& sed -i 's/^exit.*/exit 0/' /sbin/initctl \
		&& echo 'force-unsafe-io' > /etc/dpkg/dpkg.cfg.d/docker-apt-speedup \
		&& echo 'DPkg::Post-Invoke { "rm -f /var/cache/apt/archives/*.deb /var/cache/apt/archives/partial/*.deb /var/cache/apt/*.bin || true"; };' > /etc/apt/apt.conf.d/docker-clean \
	&& echo 'APT::Update::Post-Invoke { "rm -f /var/cache/apt/archives/*.deb /var/cache/apt/archives/partial/*.deb /var/cache/apt/*.bin || true"; };' >> /etc/apt/apt.conf.d/docker-clean \
	&& echo 'Dir::Cache::pkgcache ""; Dir::Cache::srcpkgcache "";' >> /etc/apt/apt.conf.d/docker-clean \
		&& echo 'Acquire::Languages "none";' > /etc/apt/apt.conf.d/docker-no-languages \
		&& echo 'Acquire::GzipIndexes "true"; Acquire::CompressionTypes::Order:: "gz";' > /etc/apt/apt.conf.d/docker-gzip-indexes
```

-	Created: Fri, 20 Nov 2015 04:57:24 GMT
-	Parent Layer: `f951648fc00de32c256043a6cfc0c16545547aa696318361f5e72709d558135e`
-	Docker Version: 1.8.3
-	Virtual Size: 701.0 B
-	v2 Blob: `sha256:8e234ff2f9273864f919a11ef87f3e47fd7592038c1d4754916045aa9eb21651`
-	v2 Content-Length: 759.0 B
-	v2 Last-Modified: Fri, 20 Nov 2015 05:02:25 GMT

#### `d9b1b9e57d8e7971041d2753e78f6931a06053bd4633a6567b352c3a30e674b6`

```dockerfile
RUN sed -i 's/^#\s*\(deb.*universe\)$/\1/g' /etc/apt/sources.list
```

-	Created: Fri, 20 Nov 2015 04:57:26 GMT
-	Parent Layer: `213b4a4f666de4dad35ac1545b6d7eb9086a5f949921532c292869707e7adb30`
-	Docker Version: 1.8.3
-	Virtual Size: 1.9 KB (1879 bytes)
-	v2 Blob: `sha256:a71b7b742fee2c204426d9a193a56f3ea223eef84810b85c1840811663ca5dcb`
-	v2 Content-Length: 677.0 B
-	v2 Last-Modified: Fri, 20 Nov 2015 05:02:20 GMT

#### `db672630245b8058c9886e94edf869f951289bdbb6f088f458681cf4636a162a`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Fri, 20 Nov 2015 04:57:26 GMT
-	Parent Layer: `d9b1b9e57d8e7971041d2753e78f6931a06053bd4633a6567b352c3a30e674b6`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `401596022d7ae8c775e489219fc94b34a3dbbffaddc0f73a6a324ef485ce249b`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 20 Nov 2015 05:12:22 GMT
-	Parent Layer: `db672630245b8058c9886e94edf869f951289bdbb6f088f458681cf4636a162a`
-	Docker Version: 1.8.3
-	Virtual Size: 16.1 MB (16120403 bytes)
-	v2 Blob: `sha256:90c6cb01029bb11efaa4e5175e6a3fd48274bc8dbcc51de67108a94cef413764`
-	v2 Content-Length: 6.8 MB (6838186 bytes)
-	v2 Last-Modified: Fri, 20 Nov 2015 05:41:32 GMT

#### `f1115ccafdf3fd2947ee00f0ae1571999992b328bfb6a45289c751f708b59284`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Wed, 25 Nov 2015 17:04:02 GMT
-	Parent Layer: `401596022d7ae8c775e489219fc94b34a3dbbffaddc0f73a6a324ef485ce249b`
-	Docker Version: 1.8.3
-	Virtual Size: 112.1 MB (112122415 bytes)
-	v2 Blob: `sha256:4f77f03ad84164269a4dd1c5def3c1427d87961d81d6a4a0d8fce47a8a2040fa`
-	v2 Content-Length: 37.5 MB (37483813 bytes)
-	v2 Last-Modified: Wed, 25 Nov 2015 18:18:28 GMT

#### `2ffe4851a4d12bcb299aefd47bade3392d8e261ae021569c51e8aa9aca3d53bf`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Wed, 25 Nov 2015 17:07:46 GMT
-	Parent Layer: `f1115ccafdf3fd2947ee00f0ae1571999992b328bfb6a45289c751f708b59284`
-	Docker Version: 1.8.3
-	Virtual Size: 340.5 MB (340496543 bytes)
-	v2 Blob: `sha256:c7743d084391e17804e1e59de943156b9eaf3fce9c42a6180031184645ab4d26`
-	v2 Content-Length: 126.8 MB (126840061 bytes)
-	v2 Last-Modified: Wed, 25 Nov 2015 18:20:13 GMT

## `buildpack-deps:wheezy-curl`

```console
$ docker pull library/buildpack-deps@sha256:a581434e893f75304c2fadb7fd5ba9dd915083e60d73995ab6a88d1fa323573b
```

-	Total Virtual Size: 99.1 MB (99079228 bytes)
-	Total v2 Content-Length: 43.9 MB (43913262 bytes)

### Layers (3)

#### `2c788329cf71b09863a2ba17dc0275d7f89c2890f04c0c6195313c5c37e09215`

```dockerfile
ADD file:ea7fb7f89a81c9be7ab4abf1bfb1310d2566104701c6543301bdf27818891015 in /
```

-	Created: Fri, 04 Dec 2015 19:31:07 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 84.9 MB (84894442 bytes)
-	v2 Blob: `sha256:45a5ec39a81f3ae44630f998adad19965c29d5bfb3ae4caabefccf39159a9076`
-	v2 Content-Length: 37.2 MB (37184719 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 19:55:23 GMT

#### `c1661b87f43627a9e630109963c7c135ff6f5819a42c4e0fb14d1ea653d5ba29`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Fri, 04 Dec 2015 19:31:10 GMT
-	Parent Layer: `2c788329cf71b09863a2ba17dc0275d7f89c2890f04c0c6195313c5c37e09215`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `797260d1b3fadb10887a052e3bb580ae0f5598d44fbfa96d975b3b2dad48e329`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:42:56 GMT
-	Parent Layer: `c1661b87f43627a9e630109963c7c135ff6f5819a42c4e0fb14d1ea653d5ba29`
-	Docker Version: 1.8.3
-	Virtual Size: 14.2 MB (14184786 bytes)
-	v2 Blob: `sha256:fa53b03ee1078bc309c0499b80d4e93cc9850e4c9744e5d6bc738297bdca1c7c`
-	v2 Content-Length: 6.7 MB (6728511 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 20:15:52 GMT

## `buildpack-deps:wheezy-scm`

```console
$ docker pull library/buildpack-deps@sha256:f790160909b19571fb66a9089f564cab8466d14cd0a2690d6752ff3cc116d3b4
```

-	Total Virtual Size: 209.1 MB (209088737 bytes)
-	Total v2 Content-Length: 81.3 MB (81267856 bytes)

### Layers (4)

#### `2c788329cf71b09863a2ba17dc0275d7f89c2890f04c0c6195313c5c37e09215`

```dockerfile
ADD file:ea7fb7f89a81c9be7ab4abf1bfb1310d2566104701c6543301bdf27818891015 in /
```

-	Created: Fri, 04 Dec 2015 19:31:07 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 84.9 MB (84894442 bytes)
-	v2 Blob: `sha256:45a5ec39a81f3ae44630f998adad19965c29d5bfb3ae4caabefccf39159a9076`
-	v2 Content-Length: 37.2 MB (37184719 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 19:55:23 GMT

#### `c1661b87f43627a9e630109963c7c135ff6f5819a42c4e0fb14d1ea653d5ba29`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Fri, 04 Dec 2015 19:31:10 GMT
-	Parent Layer: `2c788329cf71b09863a2ba17dc0275d7f89c2890f04c0c6195313c5c37e09215`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `797260d1b3fadb10887a052e3bb580ae0f5598d44fbfa96d975b3b2dad48e329`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:42:56 GMT
-	Parent Layer: `c1661b87f43627a9e630109963c7c135ff6f5819a42c4e0fb14d1ea653d5ba29`
-	Docker Version: 1.8.3
-	Virtual Size: 14.2 MB (14184786 bytes)
-	v2 Blob: `sha256:fa53b03ee1078bc309c0499b80d4e93cc9850e4c9744e5d6bc738297bdca1c7c`
-	v2 Content-Length: 6.7 MB (6728511 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 20:15:52 GMT

#### `36771c76c1fade56f5361f9f8549ba5a01028abd616989427ecdc4afda991ea4`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:43:24 GMT
-	Parent Layer: `797260d1b3fadb10887a052e3bb580ae0f5598d44fbfa96d975b3b2dad48e329`
-	Docker Version: 1.8.3
-	Virtual Size: 110.0 MB (110009509 bytes)
-	v2 Blob: `sha256:5148621583f4827916990de51d95dbe61b4b7863633d60a511e134cc7a95d486`
-	v2 Content-Length: 37.4 MB (37354594 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 20:17:04 GMT

## `buildpack-deps:wheezy`

```console
$ docker pull library/buildpack-deps@sha256:753f5fc57793fbd415f16d4e9451f34f623c4453f80a12474d2c72f818daa9e6
```

-	Total Virtual Size: 459.6 MB (459648074 bytes)
-	Total v2 Content-Length: 175.6 MB (175551804 bytes)

### Layers (5)

#### `2c788329cf71b09863a2ba17dc0275d7f89c2890f04c0c6195313c5c37e09215`

```dockerfile
ADD file:ea7fb7f89a81c9be7ab4abf1bfb1310d2566104701c6543301bdf27818891015 in /
```

-	Created: Fri, 04 Dec 2015 19:31:07 GMT
-	Docker Version: 1.8.3
-	Virtual Size: 84.9 MB (84894442 bytes)
-	v2 Blob: `sha256:45a5ec39a81f3ae44630f998adad19965c29d5bfb3ae4caabefccf39159a9076`
-	v2 Content-Length: 37.2 MB (37184719 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 19:55:23 GMT

#### `c1661b87f43627a9e630109963c7c135ff6f5819a42c4e0fb14d1ea653d5ba29`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Fri, 04 Dec 2015 19:31:10 GMT
-	Parent Layer: `2c788329cf71b09863a2ba17dc0275d7f89c2890f04c0c6195313c5c37e09215`
-	Docker Version: 1.8.3
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `797260d1b3fadb10887a052e3bb580ae0f5598d44fbfa96d975b3b2dad48e329`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:42:56 GMT
-	Parent Layer: `c1661b87f43627a9e630109963c7c135ff6f5819a42c4e0fb14d1ea653d5ba29`
-	Docker Version: 1.8.3
-	Virtual Size: 14.2 MB (14184786 bytes)
-	v2 Blob: `sha256:fa53b03ee1078bc309c0499b80d4e93cc9850e4c9744e5d6bc738297bdca1c7c`
-	v2 Content-Length: 6.7 MB (6728511 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 20:15:52 GMT

#### `36771c76c1fade56f5361f9f8549ba5a01028abd616989427ecdc4afda991ea4`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:43:24 GMT
-	Parent Layer: `797260d1b3fadb10887a052e3bb580ae0f5598d44fbfa96d975b3b2dad48e329`
-	Docker Version: 1.8.3
-	Virtual Size: 110.0 MB (110009509 bytes)
-	v2 Blob: `sha256:5148621583f4827916990de51d95dbe61b4b7863633d60a511e134cc7a95d486`
-	v2 Content-Length: 37.4 MB (37354594 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 20:17:04 GMT

#### `dcc6593f325a889f1a42be2df7ec55885c45524193ad304356ed2d13ef04bdf4`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Fri, 04 Dec 2015 19:44:37 GMT
-	Parent Layer: `36771c76c1fade56f5361f9f8549ba5a01028abd616989427ecdc4afda991ea4`
-	Docker Version: 1.8.3
-	Virtual Size: 250.6 MB (250559337 bytes)
-	v2 Blob: `sha256:883ea40d233a87af0de2f502d2630e834ab5b5127c4868c1a6e4854795b95935`
-	v2 Content-Length: 94.3 MB (94283948 bytes)
-	v2 Last-Modified: Fri, 04 Dec 2015 20:18:31 GMT

## `buildpack-deps:wily-curl`

```console
$ docker pull library/buildpack-deps@sha256:0f9748eaced4cd689685a3df30c99ef5dbe5255c1b862f75eb1c43438c34d6c9
```

-	Total Virtual Size: 148.3 MB (148304455 bytes)
-	Total v2 Content-Length: 57.0 MB (57042321 bytes)

### Layers (5)

#### `8e5a0678471d9da53bb5338c74bb0baee8b3e87c4e9c3912e4af8088cf37d9c4`

```dockerfile
ADD file:e5047034dfd852d469840c5351e992b98073c19453c2352a7b59bd57013b1628 in /
```

-	Created: Thu, 22 Oct 2015 21:58:41 GMT
-	Docker Version: 1.8.2
-	Virtual Size: 131.4 MB (131385666 bytes)
-	v2 Blob: `sha256:1a0008b463fe37a2c50ee120e9383ccc4423dc776130dd205bff2de85737c190`
-	v2 Content-Length: 49.8 MB (49815863 bytes)
-	v2 Last-Modified: Thu, 22 Oct 2015 22:17:36 GMT

#### `796a82f1e61b05c4a8eda74da2c815ad7ee672929f099b57f870a9bd10dfec40`

```dockerfile
RUN echo '#!/bin/sh' > /usr/sbin/policy-rc.d \
	&& echo 'exit 101' >> /usr/sbin/policy-rc.d \
	&& chmod +x /usr/sbin/policy-rc.d \
		&& dpkg-divert --local --rename --add /sbin/initctl \
	&& cp -a /usr/sbin/policy-rc.d /sbin/initctl \
	&& sed -i 's/^exit.*/exit 0/' /sbin/initctl \
		&& echo 'force-unsafe-io' > /etc/dpkg/dpkg.cfg.d/docker-apt-speedup \
		&& echo 'DPkg::Post-Invoke { "rm -f /var/cache/apt/archives/*.deb /var/cache/apt/archives/partial/*.deb /var/cache/apt/*.bin || true"; };' > /etc/apt/apt.conf.d/docker-clean \
	&& echo 'APT::Update::Post-Invoke { "rm -f /var/cache/apt/archives/*.deb /var/cache/apt/archives/partial/*.deb /var/cache/apt/*.bin || true"; };' >> /etc/apt/apt.conf.d/docker-clean \
	&& echo 'Dir::Cache::pkgcache ""; Dir::Cache::srcpkgcache "";' >> /etc/apt/apt.conf.d/docker-clean \
		&& echo 'Acquire::Languages "none";' > /etc/apt/apt.conf.d/docker-no-languages \
		&& echo 'Acquire::GzipIndexes "true"; Acquire::CompressionTypes::Order:: "gz";' > /etc/apt/apt.conf.d/docker-gzip-indexes
```

-	Created: Thu, 22 Oct 2015 21:58:45 GMT
-	Parent Layer: `8e5a0678471d9da53bb5338c74bb0baee8b3e87c4e9c3912e4af8088cf37d9c4`
-	Docker Version: 1.8.2
-	Virtual Size: 701.0 B
-	v2 Blob: `sha256:b71b9c2876d6e2ff3fd610d99389be852e88a73f47218e80605c8b6a4e9fa063`
-	v2 Content-Length: 758.0 B
-	v2 Last-Modified: Thu, 22 Oct 2015 22:17:07 GMT

#### `793f61127cbb9196e9cc3b20a2e2f720dd69307172ebf28b505a9cfd67437cf6`

```dockerfile
RUN sed -i 's/^#\s*\(deb.*universe\)$/\1/g' /etc/apt/sources.list
```

-	Created: Thu, 22 Oct 2015 21:58:47 GMT
-	Parent Layer: `796a82f1e61b05c4a8eda74da2c815ad7ee672929f099b57f870a9bd10dfec40`
-	Docker Version: 1.8.2
-	Virtual Size: 1.9 KB (1863 bytes)
-	v2 Blob: `sha256:a8dc14ea182a05eb94df77525a9df9d75002e35016cdbc3bec70ffd9813c4798`
-	v2 Content-Length: 682.0 B
-	v2 Last-Modified: Thu, 22 Oct 2015 22:17:02 GMT

#### `337d0fd75c93aa307e1ea4285ce147eff9653f53044860a84253cdd1ad5dc539`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 22 Oct 2015 21:58:47 GMT
-	Parent Layer: `793f61127cbb9196e9cc3b20a2e2f720dd69307172ebf28b505a9cfd67437cf6`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f2deaace226318160a5a79a0592b562e48ef973e89ddaaa6b941f0ddd0cb0dbc`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 22 Oct 2015 22:56:17 GMT
-	Parent Layer: `337d0fd75c93aa307e1ea4285ce147eff9653f53044860a84253cdd1ad5dc539`
-	Docker Version: 1.8.2
-	Virtual Size: 16.9 MB (16916225 bytes)
-	v2 Blob: `sha256:4aa145fdd6788ab5044ca71859d47cce3c315ed8fd6b9c9859d419cd1552e46b`
-	v2 Content-Length: 7.2 MB (7224986 bytes)
-	v2 Last-Modified: Thu, 22 Oct 2015 23:49:43 GMT

## `buildpack-deps:wily-scm`

```console
$ docker pull library/buildpack-deps@sha256:90746dd071db9cde731c22751343aec559db05f415b4b77415b790439fc2f93a
```

-	Total Virtual Size: 261.8 MB (261830552 bytes)
-	Total v2 Content-Length: 95.1 MB (95052525 bytes)

### Layers (6)

#### `8e5a0678471d9da53bb5338c74bb0baee8b3e87c4e9c3912e4af8088cf37d9c4`

```dockerfile
ADD file:e5047034dfd852d469840c5351e992b98073c19453c2352a7b59bd57013b1628 in /
```

-	Created: Thu, 22 Oct 2015 21:58:41 GMT
-	Docker Version: 1.8.2
-	Virtual Size: 131.4 MB (131385666 bytes)
-	v2 Blob: `sha256:1a0008b463fe37a2c50ee120e9383ccc4423dc776130dd205bff2de85737c190`
-	v2 Content-Length: 49.8 MB (49815863 bytes)
-	v2 Last-Modified: Thu, 22 Oct 2015 22:17:36 GMT

#### `796a82f1e61b05c4a8eda74da2c815ad7ee672929f099b57f870a9bd10dfec40`

```dockerfile
RUN echo '#!/bin/sh' > /usr/sbin/policy-rc.d \
	&& echo 'exit 101' >> /usr/sbin/policy-rc.d \
	&& chmod +x /usr/sbin/policy-rc.d \
		&& dpkg-divert --local --rename --add /sbin/initctl \
	&& cp -a /usr/sbin/policy-rc.d /sbin/initctl \
	&& sed -i 's/^exit.*/exit 0/' /sbin/initctl \
		&& echo 'force-unsafe-io' > /etc/dpkg/dpkg.cfg.d/docker-apt-speedup \
		&& echo 'DPkg::Post-Invoke { "rm -f /var/cache/apt/archives/*.deb /var/cache/apt/archives/partial/*.deb /var/cache/apt/*.bin || true"; };' > /etc/apt/apt.conf.d/docker-clean \
	&& echo 'APT::Update::Post-Invoke { "rm -f /var/cache/apt/archives/*.deb /var/cache/apt/archives/partial/*.deb /var/cache/apt/*.bin || true"; };' >> /etc/apt/apt.conf.d/docker-clean \
	&& echo 'Dir::Cache::pkgcache ""; Dir::Cache::srcpkgcache "";' >> /etc/apt/apt.conf.d/docker-clean \
		&& echo 'Acquire::Languages "none";' > /etc/apt/apt.conf.d/docker-no-languages \
		&& echo 'Acquire::GzipIndexes "true"; Acquire::CompressionTypes::Order:: "gz";' > /etc/apt/apt.conf.d/docker-gzip-indexes
```

-	Created: Thu, 22 Oct 2015 21:58:45 GMT
-	Parent Layer: `8e5a0678471d9da53bb5338c74bb0baee8b3e87c4e9c3912e4af8088cf37d9c4`
-	Docker Version: 1.8.2
-	Virtual Size: 701.0 B
-	v2 Blob: `sha256:b71b9c2876d6e2ff3fd610d99389be852e88a73f47218e80605c8b6a4e9fa063`
-	v2 Content-Length: 758.0 B
-	v2 Last-Modified: Thu, 22 Oct 2015 22:17:07 GMT

#### `793f61127cbb9196e9cc3b20a2e2f720dd69307172ebf28b505a9cfd67437cf6`

```dockerfile
RUN sed -i 's/^#\s*\(deb.*universe\)$/\1/g' /etc/apt/sources.list
```

-	Created: Thu, 22 Oct 2015 21:58:47 GMT
-	Parent Layer: `796a82f1e61b05c4a8eda74da2c815ad7ee672929f099b57f870a9bd10dfec40`
-	Docker Version: 1.8.2
-	Virtual Size: 1.9 KB (1863 bytes)
-	v2 Blob: `sha256:a8dc14ea182a05eb94df77525a9df9d75002e35016cdbc3bec70ffd9813c4798`
-	v2 Content-Length: 682.0 B
-	v2 Last-Modified: Thu, 22 Oct 2015 22:17:02 GMT

#### `337d0fd75c93aa307e1ea4285ce147eff9653f53044860a84253cdd1ad5dc539`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 22 Oct 2015 21:58:47 GMT
-	Parent Layer: `793f61127cbb9196e9cc3b20a2e2f720dd69307172ebf28b505a9cfd67437cf6`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f2deaace226318160a5a79a0592b562e48ef973e89ddaaa6b941f0ddd0cb0dbc`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 22 Oct 2015 22:56:17 GMT
-	Parent Layer: `337d0fd75c93aa307e1ea4285ce147eff9653f53044860a84253cdd1ad5dc539`
-	Docker Version: 1.8.2
-	Virtual Size: 16.9 MB (16916225 bytes)
-	v2 Blob: `sha256:4aa145fdd6788ab5044ca71859d47cce3c315ed8fd6b9c9859d419cd1552e46b`
-	v2 Content-Length: 7.2 MB (7224986 bytes)
-	v2 Last-Modified: Thu, 22 Oct 2015 23:49:43 GMT

#### `a0a65171cc78af92ca9b4df427899f334083489dfc39a17a0b7eedc7d4bd467e`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Wed, 25 Nov 2015 17:12:36 GMT
-	Parent Layer: `f2deaace226318160a5a79a0592b562e48ef973e89ddaaa6b941f0ddd0cb0dbc`
-	Docker Version: 1.8.3
-	Virtual Size: 113.5 MB (113526097 bytes)
-	v2 Blob: `sha256:3ee27126c15e5b7321e3b50e06f6ed855fc3a60001d701c622272571b9c1f666`
-	v2 Content-Length: 38.0 MB (38010204 bytes)
-	v2 Last-Modified: Wed, 25 Nov 2015 18:25:09 GMT

## `buildpack-deps:wily`

```console
$ docker pull library/buildpack-deps@sha256:6128366c554bc50df5a825cfe920cba77dfcc8e813fb39538716090c00d801c0
```

-	Total Virtual Size: 633.6 MB (633626253 bytes)
-	Total v2 Content-Length: 229.2 MB (229176443 bytes)

### Layers (7)

#### `8e5a0678471d9da53bb5338c74bb0baee8b3e87c4e9c3912e4af8088cf37d9c4`

```dockerfile
ADD file:e5047034dfd852d469840c5351e992b98073c19453c2352a7b59bd57013b1628 in /
```

-	Created: Thu, 22 Oct 2015 21:58:41 GMT
-	Docker Version: 1.8.2
-	Virtual Size: 131.4 MB (131385666 bytes)
-	v2 Blob: `sha256:1a0008b463fe37a2c50ee120e9383ccc4423dc776130dd205bff2de85737c190`
-	v2 Content-Length: 49.8 MB (49815863 bytes)
-	v2 Last-Modified: Thu, 22 Oct 2015 22:17:36 GMT

#### `796a82f1e61b05c4a8eda74da2c815ad7ee672929f099b57f870a9bd10dfec40`

```dockerfile
RUN echo '#!/bin/sh' > /usr/sbin/policy-rc.d \
	&& echo 'exit 101' >> /usr/sbin/policy-rc.d \
	&& chmod +x /usr/sbin/policy-rc.d \
		&& dpkg-divert --local --rename --add /sbin/initctl \
	&& cp -a /usr/sbin/policy-rc.d /sbin/initctl \
	&& sed -i 's/^exit.*/exit 0/' /sbin/initctl \
		&& echo 'force-unsafe-io' > /etc/dpkg/dpkg.cfg.d/docker-apt-speedup \
		&& echo 'DPkg::Post-Invoke { "rm -f /var/cache/apt/archives/*.deb /var/cache/apt/archives/partial/*.deb /var/cache/apt/*.bin || true"; };' > /etc/apt/apt.conf.d/docker-clean \
	&& echo 'APT::Update::Post-Invoke { "rm -f /var/cache/apt/archives/*.deb /var/cache/apt/archives/partial/*.deb /var/cache/apt/*.bin || true"; };' >> /etc/apt/apt.conf.d/docker-clean \
	&& echo 'Dir::Cache::pkgcache ""; Dir::Cache::srcpkgcache "";' >> /etc/apt/apt.conf.d/docker-clean \
		&& echo 'Acquire::Languages "none";' > /etc/apt/apt.conf.d/docker-no-languages \
		&& echo 'Acquire::GzipIndexes "true"; Acquire::CompressionTypes::Order:: "gz";' > /etc/apt/apt.conf.d/docker-gzip-indexes
```

-	Created: Thu, 22 Oct 2015 21:58:45 GMT
-	Parent Layer: `8e5a0678471d9da53bb5338c74bb0baee8b3e87c4e9c3912e4af8088cf37d9c4`
-	Docker Version: 1.8.2
-	Virtual Size: 701.0 B
-	v2 Blob: `sha256:b71b9c2876d6e2ff3fd610d99389be852e88a73f47218e80605c8b6a4e9fa063`
-	v2 Content-Length: 758.0 B
-	v2 Last-Modified: Thu, 22 Oct 2015 22:17:07 GMT

#### `793f61127cbb9196e9cc3b20a2e2f720dd69307172ebf28b505a9cfd67437cf6`

```dockerfile
RUN sed -i 's/^#\s*\(deb.*universe\)$/\1/g' /etc/apt/sources.list
```

-	Created: Thu, 22 Oct 2015 21:58:47 GMT
-	Parent Layer: `796a82f1e61b05c4a8eda74da2c815ad7ee672929f099b57f870a9bd10dfec40`
-	Docker Version: 1.8.2
-	Virtual Size: 1.9 KB (1863 bytes)
-	v2 Blob: `sha256:a8dc14ea182a05eb94df77525a9df9d75002e35016cdbc3bec70ffd9813c4798`
-	v2 Content-Length: 682.0 B
-	v2 Last-Modified: Thu, 22 Oct 2015 22:17:02 GMT

#### `337d0fd75c93aa307e1ea4285ce147eff9653f53044860a84253cdd1ad5dc539`

```dockerfile
CMD ["/bin/bash"]
```

-	Created: Thu, 22 Oct 2015 21:58:47 GMT
-	Parent Layer: `793f61127cbb9196e9cc3b20a2e2f720dd69307172ebf28b505a9cfd67437cf6`
-	Docker Version: 1.8.2
-	Virtual Size: 0.0 B
-	v2 Blob: `sha256:a3ed95caeb02ffe68cdd9fd84406680ae93d633cb16422d00e8a7c22955b46d4`
-	v2 Content-Length: 32.0 B
-	v2 Last-Modified: Sat, 14 Nov 2015 09:09:44 GMT

#### `f2deaace226318160a5a79a0592b562e48ef973e89ddaaa6b941f0ddd0cb0dbc`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		ca-certificates \
		curl \
		wget \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Thu, 22 Oct 2015 22:56:17 GMT
-	Parent Layer: `337d0fd75c93aa307e1ea4285ce147eff9653f53044860a84253cdd1ad5dc539`
-	Docker Version: 1.8.2
-	Virtual Size: 16.9 MB (16916225 bytes)
-	v2 Blob: `sha256:4aa145fdd6788ab5044ca71859d47cce3c315ed8fd6b9c9859d419cd1552e46b`
-	v2 Content-Length: 7.2 MB (7224986 bytes)
-	v2 Last-Modified: Thu, 22 Oct 2015 23:49:43 GMT

#### `a0a65171cc78af92ca9b4df427899f334083489dfc39a17a0b7eedc7d4bd467e`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		bzr \
		git \
		mercurial \
		openssh-client \
		subversion \
				procps \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Wed, 25 Nov 2015 17:12:36 GMT
-	Parent Layer: `f2deaace226318160a5a79a0592b562e48ef973e89ddaaa6b941f0ddd0cb0dbc`
-	Docker Version: 1.8.3
-	Virtual Size: 113.5 MB (113526097 bytes)
-	v2 Blob: `sha256:3ee27126c15e5b7321e3b50e06f6ed855fc3a60001d701c622272571b9c1f666`
-	v2 Content-Length: 38.0 MB (38010204 bytes)
-	v2 Last-Modified: Wed, 25 Nov 2015 18:25:09 GMT

#### `f2bf5ca6404ab2c05539a54c2dfd2d799cf4bdf78f87d7620af9fa41ef4da33c`

```dockerfile
RUN apt-get update && apt-get install -y --no-install-recommends \
		autoconf \
		automake \
		bzip2 \
		file \
		g++ \
		gcc \
		imagemagick \
		libbz2-dev \
		libc6-dev \
		libcurl4-openssl-dev \
		libevent-dev \
		libffi-dev \
		libgeoip-dev \
		libglib2.0-dev \
		libjpeg-dev \
		liblzma-dev \
		libmagickcore-dev \
		libmagickwand-dev \
		libmysqlclient-dev \
		libncurses-dev \
		libpng-dev \
		libpq-dev \
		libreadline-dev \
		libsqlite3-dev \
		libssl-dev \
		libtool \
		libwebp-dev \
		libxml2-dev \
		libxslt-dev \
		libyaml-dev \
		make \
		patch \
		xz-utils \
		zlib1g-dev \
	&& rm -rf /var/lib/apt/lists/*
```

-	Created: Wed, 25 Nov 2015 17:17:08 GMT
-	Parent Layer: `a0a65171cc78af92ca9b4df427899f334083489dfc39a17a0b7eedc7d4bd467e`
-	Docker Version: 1.8.3
-	Virtual Size: 371.8 MB (371795701 bytes)
-	v2 Blob: `sha256:dc0a7af973e955655e488ac9bff7bdd108d81cda04bef60e6eb8e30ec606f3aa`
-	v2 Content-Length: 134.1 MB (134123918 bytes)
-	v2 Last-Modified: Wed, 25 Nov 2015 18:26:46 GMT
