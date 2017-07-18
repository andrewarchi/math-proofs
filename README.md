# Pi by the sum of inverse squares

$$\frac{\pi^2}{6} = \sum_{n=1}^{\infty}\frac{1}{n^2}$$

# Pi by inverse tangent Taylor series

$$\arctan x = x - \frac{x^3}{3} + \frac{x^5}{5} - \frac{x^7}{7} + \frac{x^9}{9} - \cdots$$
$$= \sum_{n=0}^{\infty} (-1)^n \frac{x^{2n + 1}}{2n + 1}$$
$$x \in [-1, 1]$$
$$\frac{\pi}{4} = \arctan 1
= \sum_{n=0}^{\infty} \frac{(-1)^n}{2n + 1}$$

# Pi by inscribed and circumscribed polygons

## Inscribed

### Law of sines

$$\frac{\sin(\frac{\pi}{2}-\frac{\pi}{n})}{r} = \frac{\sin\frac{2\pi}{n}}{l}$$
$$= \frac{\cos\frac{\pi}{n}}{r} = \frac{2\sin\frac{\pi}{n}\cos\frac{\pi}{n}}{l}$$
$$l = 2r\sin\frac{\pi}{n}$$
$$P = ln
= 2rn\sin\frac{\pi}{n}$$

### Law of cosines

$$l^2 = 2r^2 - 2r^2cos\frac{2\pi}{n}
= 2r^2(1 - cos\frac{2\pi}{n})
= 4r^2(\frac{1 - cos\frac{2\pi}{n}}{2})
= 4r^2\sin^2{\frac{\pi}{n}}$$
$$l = 2r\sin\frac{\pi}{n} = r\sqrt{2 - 2\cos\frac{2\pi}{n}}$$
$$P = 2nrsin\frac{\pi}{n}$$

### Pythagorean theorem

$$r^2 = (\frac{l}{2})^2 + h^2$$
$$h^2 = r^2 - \frac{1}{4}l^2
= r^2 - r^2\sin^2\frac{\pi}{n}
= r^2(1 - \sin^2\frac{\pi}{n})
= r^2\cos^2\frac{\pi}{n}$$
$$h = r\cos\frac{\pi}{n}$$
$$A = \frac{1}{2}lhn
= \frac{1}{2}(2r\sin\frac{\pi}{n})(rcos\frac{\pi}{n})(n)
= nr^2\sin\frac{\pi}{n}\cos\frac{\pi}{n}
= \frac{1}{2}nr^2\sin\frac{2\pi}{n}$$

### Results

Perimeter

$$2\pi{r} = \lim_{n\to\infty} P
= \lim_{n\to\infty} 2rn\sin\frac{\pi}{n}$$

Area

$$\pi{r^2} = \lim_{n\to\infty} \frac{1}{2}nr^2\sin\frac{2\pi}{n}$$
$$\pi = \lim_{n\to\infty} \frac{1}{2}n\sin\frac{2\pi}{n}
= \lim_{n\to\infty} n\sin\frac{\pi}{n}\cos\frac{\pi}{n}$$

## Circumscribed

### Law of sines

$$\frac{\sin\frac{\pi}{n}}{L} = \frac{\sin(\pi - \frac{2\pi}{n})}{l}$$
$$\sin(\pi - \frac{2\pi}{n}) = \sin[2(\frac{\pi}{2} - \frac{\pi}{n})]
= 2\sin(\frac{\pi}{2} - \frac{\pi}{n})\cos(\frac{\pi}{2} - \frac{\pi}{n})
= 2\sin\frac{\pi}{n}\cos\frac{\pi}{n}$$
$$L = \frac{l\sin\frac{\pi}{n}}{2\sin\frac{\pi}{n}\cos\frac{\pi}{n}}
= \frac{1}{2}l\sec\frac{\pi}{n}
= \frac{1}{2}(2r\sin\frac{\pi}{n})\sec\frac{\pi}{n}
= r\tan\frac{\pi}{n}$$

### Law of cosines

$$l^2 = 2L^2 - 2L^2cos\frac{\pi - 2\pi}{n}
= L^2(2 - 2\cos(\pi - \frac{2\pi}{n}))$$
$$\cos(\pi - \frac{2\pi}{n}) = \cos[2(\frac{\pi}{2} - \frac{\pi}{n})]
= 1 - 2\sin^2(\frac{\pi}{2} - \frac{\pi}{n})
= 1 - 2\cos^2\frac{\pi}{2}$$
$$l^2 = L^2[2 - 2(1 - 2\cos^2\frac{\pi}{n})]
= 4L^2\cos^2\frac{\pi}{n}$$
$$l = 2L\cos\frac{\pi}{n}$$
$$2r\sin\frac{\pi}{n} = 2L\cos{\pi}{n}$$
$$L = r\tan\frac{\pi}{n}$$

### Pythagorean theorem

$$L^2 = (\frac{l}{2})^2 + H^2$$
$$H^2 = r^2tan^2\frac{\pi}{n} - r^2\sin^2\frac{\pi}{n}
= r^2(\tan^2\frac{\pi}{n} - \sin^2\frac{\pi}{n})$$
$$tan^2\frac{\pi}{n} - \sin^2\frac{\pi}{n} = tan^2\frac{\pi}{n} - \cos^2\frac{\pi}{2}\tan\frac{\pi}{2}
= \tan^2\frac{\pi}{n}(1 - \cos^2\frac{\pi}{n})
= \sin^2\frac{\pi}{n}tan^2\frac{\pi}{n}$$
$$H^2 = R^2sin^2\frac{\pi}{n}\tan^2{\pi}{n}$$
$$H = r\sin\frac{\pi}{n}\tan\frac{\pi}{n}$$

### Results

Perimeter

$$P = 2nL = 2nr\tan\frac{\pi}{n}$$
$$2\pi{r} = \lim_{n\to\infty} 2nr\tan\frac{\pi}{n}$$
$$\pi = \lim_{n\to\infty} n\tan\frac{\pi}{n}$$

Area

$$A = nH\frac{L}{2} + A_l$$
$$  = n(r\sin\frac{\pi}{n}\tan\frac{\pi}{n})(r\sin\frac{\pi}{n}) + A_l$$
$$  = nr^2\sin^2\frac{\pi}{n}\tan\frac{\pi}{n} + A_l$$
$$  = nr^2\sin^2\frac{\pi}{n}\tan\frac{\pi}{n} + nr^2\sin\frac{\pi}{n}\cos\frac{\pi}{n}$$
$$  = nr^2\sin\frac{\pi}{n}(\sin\frac{\pi}{n}\tan\frac{\pi}{n} + \cos\frac{\pi}{n})$$
$$  = nr^2\tan\frac{\pi}{n}(\sin^2\frac{\pi}{n} + \cos^2\frac{\pi}{n})$$
$$  = nr^2\tan\frac{\pi}{n}$$
$$\pi{r^2} = \lim_{n\to\infty} nr^2\tan\frac{\pi}{n}$$
$$\pi = \lim_{n\to\infty} n\tan\frac{\pi}{n}$$

## Simplified results

$$\pi = \lim_{n\to\infty} n\sin\frac{\pi}{n}$$
$$\pi = \lim_{n\to\infty} n\sin\frac{\pi}{n}\cos\frac{\pi}{n}$$
$$\pi = \lim_{n\to\infty} n\tan\frac{\pi}{n}$$

# Multi-dimensional spheres

$$V_1 = \int\limits_{-R}^{R} dx = 2R$$
$$V_2
= \int\limits_{-R}^{R} \int_{-\sqrt{R^2-x^2}}^{\sqrt{R^2-x^2}} dydx
= \int\limits_{-R}^{R} 2\sqrt{R^2-x^2} dx
= \int\limits_{-R}^{R} 2R\sin\arccos\frac{x}{R} dx$$
$$V_2
= \int\limits_0^{2\pi} \int\limits_0^{R} r drd\theta
= \int\limits_0^{2\pi} \frac{1}{2}R^2 d\theta
= \pi R^2$$
