# My CNCF LFX Mentorship Spring 2023 Project at Kubescape

![](lfx.png)
Project Link: [CNCF - Kubescape: Release engineering: add Kubescape to commonly-requested package managers](https://mentorship.lfx.linuxfoundation.org/project/138e9cac-ec86-43cb-a04f-c2980e3c2865)

[kubescape](https://landscape.cncf.io/card-mode?project=sandbox&selected=kubescape) is a Cloud Native Computing Foundation (CNCF) sandbox project. It is an open-source Kubernetes security platform and includes risk analysis, security compliance, and misconfiguration scanning. Targeted at the DevSecOps practitioner or platform engineer, it offers an easy-to-use CLI interface, flexible output formats, and automated scanning capabilities.

## List of things I have done
Documentations:
- [Publishing](https://github.com/kubescape/kubescape/wiki/Publishing)

Repo and Packages created:
- [kubescape/packaging](https://github.com/kubescape/packaging)
- [OpenSUSE Open Build Service home:kubescape/kubescape](https://build.opensuse.org/package/show/home:kubescape/kubescape)
- [Ubuntu Launchpad PPA kubescape/kubescape](https://launchpad.net/~kubescape/+archive/ubuntu/kubescape)
- [Chocolatey kubescape](https://community.chocolatey.org/packages/kubescape)
- [Snapcraft Store kubescape](https://snapcraft.io/kubescape)
- [Arch Linux AUR](https://aur.archlinux.org/packages/kubescape)
- [SARIF for Reviewdog](https://github.com/HollowMan6/sarif4reviewdog)

PRs opened:
- (merged) kubescape/kubescape #1095 [fix(build): LICENSE file in release tarballs](https://github.com/kubescape/kubescape/pull/1095)
- (merged) kubescape/kubescape #1105 [fix(README): broken links](https://github.com/kubescape/kubescape/pull/1105)
- (merged) kubescape/kubescape #1140 [ci(release): fix publishing krew plugin; add '.exe' extension to Windows binary](https://github.com/kubescape/kubescape/pull/1140)
- (merged) kubescape/kubescape #1147 [Change installation path to ~/.kubescape/bin](https://github.com/kubescape/kubescape/pull/1147)
- (merged) kubescape/kubescape #1148 [arm64 release binaries for CI and Krew](https://github.com/kubescape/kubescape/pull/1148)
- (merged) kubescape/kubescape #1169 [Add kubescape.exe to the release assets](https://github.com/kubescape/kubescape/pull/1169)
- (merged) kubescape/kubescape #1184 [feat(sarif): add fix object in generated reports](https://github.com/kubescape/kubescape/pull/1184)
- (merged) kubescape/kubescape #1185 [fix(fix): mixed up change summary list](https://github.com/kubescape/kubescape/pull/1185)
- (merged) kubescape/kubescape #1186 [Invoke packaging workflow to update after release](https://github.com/kubescape/kubescape/pull/1186)
- (merged) kubescape/kubescape #1196 [Move building instructions to wiki, add more installation instructions](https://github.com/kubescape/kubescape/pull/1196)
- (merged) kubescape/kubescape #1199 [Update installation script](https://github.com/kubescape/kubescape/pull/1199)
- (merged) kubescape/kubescape #1210 [ci: update before install packages](https://github.com/kubescape/kubescape/pull/1210)
- (merged) kubescape/kubescape #1213 [Deprecate kubescape-windows-latest](https://github.com/kubescape/kubescape/pull/1213)
- (merged) kubescape/kubescape #1214 [Add ref to workflow dispatch](https://github.com/kubescape/kubescape/pull/1214)
- (merged) kubescape/kubescape #1216 [Make powershell Windows installation user path available immediately](https://github.com/kubescape/kubescape/pull/1216)
- (merged) kubescape/kubescape #1236 [Deprecate kubescape-windows-latest and fix CI](https://github.com/kubescape/kubescape/pull/1236)
- (merged) kubescape/kubescape #1238 [Fix downloading arm64 binary for kubescape](https://github.com/kubescape/kubescape/pull/1238)
- (merged) kubescape/github-action #32 [Support for code reviews instead with PRs](https://github.com/kubescape/github-action/pull/32)
- (merged) kubescape/github-action #34 [Fix start new PR with own repo](https://github.com/kubescape/github-action/pull/34)
- (merged) kubescape/github-action #37 [Add exceptions parameters back](https://github.com/kubescape/github-action/pull/37)
- (merged) kubescape/github-action #38 [Keep kubescape github-action workflow up to date](https://github.com/kubescape/github-action/pull/38)
- (merged) kubescape/github-action #41 [Intergrate fix with comments](https://github.com/kubescape/github-action/pull/41)
- (merged) kubescape/github-action #42 [Version bumps start PRs instead of committing directly](https://github.com/kubescape/github-action/pull/42)
- (merged) kubescape/github-action #43 [Split the suggest fix workflow and update docs](https://github.com/kubescape/github-action/pull/43)
- (merged) kubescape/vscode-kubescape #11 [Remove platformPackages config](https://github.com/kubescape/vscode-kubescape/pull/11)
- (merged) kubescape/vscode-kubescape #12 [Bump kubescape version into v2.3.1](https://github.com/kubescape/vscode-kubescape/pull/12)
- (merged) kubescape/lens-extension #16 [Bump kubescape version into v2.3.1](https://github.com/kubescape/lens-extension/pull/16)
- (merged) kubescape/node-kubescape #3 [Support for ARM64 binaries as well as kubescape.exe](https://github.com/kubescape/node-kubescape/pull/3)
- (merged) kubescape/homebrew-tap #7 [Add Auto Release CI](https://github.com/kubescape/homebrew-tap/pull/7)
- (rejected) kubernetes-sigs/controller-runtime #2266 [🐛 Support get config inside snap with SNAP_REAL_HOME](https://github.com/kubernetes-sigs/controller-runtime/pull/2266)
- (rejected) kubernetes/kubernetes #117165 [client-go: support detect homedir with SNAP_REAL_HOME and os/user.HomeDir](https://github.com/kubernetes/kubernetes/pull/117165)
- (merged) ScoopInstaller/Main #4757 [kubescape: Update url and binary naming](https://github.com/ScoopInstaller/Main/pull/4757)
- (pending) gentoo/gentoo #30595 [sys-cluster/kubescape: new package, add 2.3.3](https://github.com/gentoo/gentoo/pull/30595)
- (merged) chocolatey-community/chocolatey-packages #2226 [(kubescape) Add Kubescape package](https://github.com/chocolatey-community/chocolatey-packages/pull/2226)

Issues opened/helped with:
- (resolved) kubescape/kubescape #195 [Provide ARM64 release binaries](https://github.com/kubescape/kubescape/issues/195)
- (resolved) kubescape/kubescape #400 [Add Kubescape to packages management for easier installation](https://github.com/kubescape/kubescape/issues/400)
- (reviewed) kubescape/kubescape #720 [Error Fixed when downloading on azure cloud vm environment](https://github.com/kubescape/kubescape/pull/720)
- (reviewed) kubescape/kubescape #1014 [Package manager support: homebrew](https://github.com/kubescape/kubescape/issues/1014)
- (resolved) kubescape/kubescape #1015 [kubescape installed in first directory in $PATH under $HOME](https://github.com/kubescape/kubescape/issues/1015)
- (helped) kubescape/kubescape #1033 [Generate SLSA provenance for builds](https://github.com/kubescape/kubescape/issues/1033)
- (reviewed) kubescape/kubescape #1112 [can't install Kubescape with krew on Apple Silicon Mac](https://github.com/kubescape/kubescape/issues/1112)
- (resolved) kubescape/kubescape #1142 [Package manager support: RPM](https://github.com/kubescape/kubescape/issues/1142)
- (resolved) kubescape/kubescape #1143 [Package manager support: deb](https://github.com/kubescape/kubescape/issues/1143)
- (resolved) kubescape/kubescape #1168 [Add kubescape.exe to the release assets to replace kubescape-windows-latest](https://github.com/kubescape/kubescape/issues/1168)
- (resolved) kubescape/kubescape #1183 [Add fix object in Kubescape generated SARIF reports when available](https://github.com/kubescape/kubescape/issues/1183)
- (reviewed) kubescape/kubescape #1215 [Fix issue 11552](https://github.com/kubescape/kubescape/pull/1215)
- (helped) kubescape/kubescape #1237 [Download and Installing Wrong Binary For Apple M1](https://github.com/kubescape/kubescape/issues/1237)
- (reviewed) kubescape/kubescape #1239 [Added instructions to setup kubescape locally](https://github.com/kubescape/kubescape/pull/1239)
- (resolved) kubescape/k8s-interface #46 [Kubescape supports getting packed as a snap app](https://github.com/kubescape/k8s-interface/issues/46)
- (resolved) kubescape/k8s-interface #46 [Kubescape supports getting packed as a snap app](https://github.com/kubescape/k8s-interface/issues/46)
- (pending response) github/community #52156 [Support code auto-fixes for GitHub Code Scanning](https://github.com/orgs/community/discussions/52156)
- (resolved) chocolatey-community #2186 [Migrate kubescape package](https://github.com/orgs/chocolatey-community/discussions/2186)
- (resolved) chocolatey-community/chocolatey-packages #2190 [(kubescape) Migrate package](https://github.com/chocolatey-community/chocolatey-packages/issues/2190)
- (resolved) snapcraft/store-requests #34661 [Request for classic confinement and name change for cli-kubescape](https://forum.snapcraft.io/t/request-for-classic-confinement-and-name-change-for-cli-kubescape/34661)
- (pending response) snapcraft/snapd #34683 [Feature Request: Stop using $SNAP_REAL_HOME to visit real home files](https://forum.snapcraft.io/t/feature-request-stop-using-snap-real-home-to-visit-real-home-files/34683)

## Project summaries
### Packaging
- [OpenSUSE Build Service (DEB and RPM)](https://build.opensuse.org/package/show/home:kubescape/kubescape)
- [RPM](https://github.com/kubescape/packaging/blob/main/kubescape.spec)
- [Ubuntu Launchpad PPA](https://github.com/kubescape/packaging/tree/main/deb/debian)
- [Homebrew Tap](https://github.com/kubescape/homebrew-tap)
- [Chocolatey](https://github.com/HollowMan6/chocolatey-packages/tree/master/automatic/kubescape)
- [Snapcraft](https://github.com/kubescape/packaging/blob/main/snap/snapcraft.yaml)
- [AUR](https://github.com/kubescape/packaging/blob/main/PKGBUILD)
- [Gentoo Portage](https://github.com/HollowMan6/gentoo/tree/kubescape/sys-cluster/kubescape)

Other packages managers that have already been available and not introduced by me during this project period:
- [OpenSUSE Zypper](https://build.opensuse.org/package/show/devel:kubic/kubescape)
- [Homebrew](https://formulae.brew.sh/formula/kubescape#default)
- [Krew](https://github.com/kubernetes-sigs/krew-index/pull/3106) (I added the ARM64 support for Krew)
- [Nix-pkgs](https://github.com/NixOS/nixpkgs/blob/master/pkgs/tools/security/kubescape/default.nix)
- [Scoop](https://scoop.sh/#/apps?q=kubescape&s=0&d=1&o=true&id=1f5ae05eaafe3e7a26505f0889101e0da91ffe91)

### GitHub Actions Release CI
I helped improve the Kubescape GitHub Actions release CI process, where I added the ARM64 build and tested for the GitHub Actions release CI workflow. I use QEMU with Docker to simulate the Linux ARM64 environment for building and testing the binaries. For macOS M1/M2, I investigated how to cross-build libgit2 C code and use Golang cross-compilation to build the binaries.

I also helped add the auto version bumping CI for [kubescape/homebrew-tap](https://github.com/kubescape/homebrew-tap/blob/main/.github/workflows/release.yml), [kubescape/packaging](https://github.com/kubescape/packaging/blob/main/.github/workflows/release.yml), and [kubescape/github-action](https://github.com/kubescape/github-action/blob/main/.github/workflows/release.yaml). After the release is made, we trigger these CIs so that the kubescape versions in these repositories can get upgraded automatically.

### GitHub Actions Code Review
I helped improve the Kubescape GitHub Actions fix suggestions code review process, where I created the workflow which works by collecting the [SARIF (Static Analysis Results Interchange Format)](https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=sarif) file that kubescape generates. Then, with the help of [HollowMan6/sarif4reviewdog](https://github.com/marketplace/actions/sarif-support-for-reviewdog), convert the SARIF file into [RDFormat (Reviewdog Diagnostic Format)](https://github.com/reviewdog/reviewdog/tree/master/proto/rdf) and generate reviews for code fix suggestions on GitHub Actions using [Reviewdog](https://github.com/reviewdog/reviewdog). I also helped add the “fix" object support for the Kubescape-generated SARIF report.

In addition to the main project, I also helped the community with other issues like bug-fixing as well as feature-adding.
