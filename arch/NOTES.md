To update checksums:

	updpkgsums

To build with cleanup afterwards: 

	makepkg -sc

Packaging workflow:
1. Compress sources and upload on server
2. test PKGBUILD
3. Compress PKGBUILD and talking-clock.install with *-arch.** in name
4. upload on server 
