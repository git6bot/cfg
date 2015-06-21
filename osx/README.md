
# Term

/etc/profile

export LC_ALL=en_US.UTF-8

uncheck Term / Settings / Advanced / International / ... on startup

# Spotlight

To disable Spotlight permanently run:

launchctl unload -w /System/Library/LaunchDaemons/com.apple.metadata.mds.plist
