## [Unreleased]

## [3.1.26] - 2018-03-20
*   fix: env var `SSH_AUTH_SOCK` not exported

## [3.1.25] - 2018-03-07
*   fix: optimize channel statements
*   feat(swapsched): set blkio read write limit for apps supported
*   chore: update license
*   fix: make gnome-keyring-daemon no hang
*   fix(keyring): fix crash because of dbus no replies
*   fix(watchdog): update dde polkit agent determine methods
*   fix: make keyring inited on goroutinue
*   fix(display): fix refresh rate set wrong
*   fix: improve launch failed messages
*   chore: fix gccgo compile failure
*   feat: add keyring to init login
*   chore: optimize launch config
*   feat: use new lib gsettings
*   refactor: add auto launch config
*   feat: setup environment in script deepin-session
*   add deepin-session
*   feat: initialize gnome keyring daemon and components
*   feat: add iowait to indicate cpu status

## [3.1.24] - 2018-01-25
*   fix: Adapt lintian
*   play logout sound via ALSA
*   startManager: launched hook supported
*   remove dde-readahead
*   update depends
*   refactor sound theme player call
*   add DE Component processes to DE cgroup
*   startManager: desktop key X-Deepin-MaximumRAM supported
*   improve calculating limit of InActiveApps
*   limit ActiveApp's minimum rss limit
*   consider ActiveApp's swap usage and reversing kernel cache
*   limit maximum limit for reversing more cache RAM
*   startManager: launch DE app in DE cgroup
*   add wm switcher
*   startManager: add method GetApps
*   update links in README
*   fix radeon detect failure
*   remove the depend 'deepin-wm-switcher'
*   use lib cgroup
*   simplify cgroups check
*   swapsched: turn limits on or off dynamically
*   improve description of uiapp opened with RunCommand
*   modify ldflags args, fix debug version not work
*   add wm watcher in watchdog
*   fix compile failed using gccgo
*   wm: fix wm switch not work if config incomplete
*   swapsched: do not set soft limit for DE group
*   make xsettings as a package

## [3.1.23] - 2017-12-13
*   add swap sched
*   launch app no scaling supported
*   startManager: fix method launch no files arg
*   refactor code about autostart
*   update makefile GOLDFLAGS
*   swap sched can control whether it is enabled in gsettings

## [3.1.22] - 2017-11-29
* display: fix primary rect wrong after rotation


## [3.1.21] - 2017-11-28
* display: sync primary settings from commandline
* disable logout sound if speaker muted


## [3.1.20] - 2017-11-22
* fix(display): sync primary rectangle when apply changes


## [3.1.19] - 2017-11-16
* fix primary rectangle wrong when output off
* correct deepin-wm-switcher config file path


## [3.1.18] - 2017-11-3
* reap children processes
* remove sound event cache before playing
* launch deepin-notifications on session start

## [3.1.17] - 2017-10-25
*   brightness: only call displayBl.List once in init ([4a232f17](4a232f17))
*   update soundutils event name ([634a9451](634a9451))


## [3.1.16] - 2017-10-12
### Added
* add window widget scale factor
* add virtual machine resolution corrector
* add 'autostop' to execute some shells before logout
* add option to start the app with proxychains

### Changed
* not scaled xresource dpi
* update license

### Fixed
* fix display modes index out