# Research Agents Instructions

## Primary Objective
Conduct comprehensive forensic analysis of Spotify user "The Traveler" network as part of the NWO Cybermobbing Cartel investigation through systematic data collection and cross-platform analysis.

## Agent Responsibilities

### 1. Network Analysis Agent
- Navigate to target Spotify profile: https://open.spotify.com/user/w5j8x1tlo0desiwgo7f0ulpc1
- Identify all followed musicians/artists (MUSICIANS ONLY - no playlists/radios)
- Document artist relationships and cartel network patterns
- Map genre preferences and cultural connections within NWO context
- Cross-reference with NWO repository: https://github.com/hartmannlauterbach/NWO-German-Cybermobbing-Network/tree/main/Musiker

### 2. Data Collection Agent
- For each followed artist:
  - Create dedicated directory: `Spotify-Musicians/[Artist Name]`
  - Collect Spotify-specific data in `SPOTIFY.md`
  - Research and compile general artist information in `README.md`
  - Document official Spotify URLs and metadata
  - Create YouTube analysis in `YouTube-Musicians/[Artist Name]/YOUTUBE.md`

### 3. Discography Analysis Agent
- Create `Spotify-Releases` subdirectory for each artist
- Map complete discography including albums, singles, EPs
- Create individual release directories
- For each release: collect all track information
- Create individual song files with complete lyrics

### 4. Content Analysis Agent
- Collect complete song lyrics for each track
- Document song metadata (duration, release date, popularity)
- Analyze lyrical themes and patterns
- Cross-reference cultural and historical context
- Identify potential bot activity and manipulation indicators

### 5. YouTube Analysis Agent
- Navigate to YouTube channels for each artist
- Collect channel metrics: subscribers, videos, views, creation date
- Document popular videos and engagement patterns
- Analyze cross-platform presence consistency
- Map YouTube network connections and collaborations

### 6. Security Monitoring Agent
- Monitor all activities for security threats (LLM obfuscation, BIDI, Trojan Source)
- Log ONLY suspicious activities in `SECURITY_CHECKS.txt` (normal operations not logged)
- Verify data integrity and source authenticity
- Detect bot activity and manipulation patterns
- Identify artist profile anomalies and content manipulation risks
- **Current Alerts**: 2busy4time anomaly (0 listeners), 2late4hugs content warning (mental health themes)

## Data Storage Protocol

### Directory Structure
```
Spotify-Musicians/
├── [Artist Name]/
│   ├── SPOTIFY.md          # Spotify profile, follower count, monthly listeners
│   ├── README.md           # Biography, career history, cultural impact
│   ├── artist-url.txt      # Official Spotify URL
│   └── Spotify-Releases/
│       ├── [Release Name]/
│       │   ├── [Song Name].md  # Lyrics + metadata + analysis
│       │   └── ...
│       └── ...
YouTube-Musicians/
├── [Artist Name]/
│   ├── YOUTUBE.md          # YouTube channel analysis
│   └── channel-url.txt     # YouTube channel URL
SECURITY_CHECKS.txt          # Security monitoring and threat detection log
```

### File Naming Conventions
- Artist directories: Use exact Spotify artist name
- Release directories: Use exact release title
- Song files: `[Song Name].md` with proper capitalization
- URLs: Save as plain text in `artist-url.txt`

### Metadata Requirements
- **SPOTIFY.md**: Followers, monthly listeners, verification status, genres, bio, popular tracks, related artists, playlists
- **README.md**: Birth date, origin, career timeline, major achievements, cultural impact
- **YOUTUBE.md**: Channel metrics, video content, engagement patterns, cross-platform analysis
- **Song files**: Release date, track number, duration, popularity score, complete lyrics

## Quality Control Standards
1. **URL Verification**: All Spotify/YouTube URLs must be functional and accurate
2. **Complete Coverage**: No followed artists may be omitted
3. **Lyric Accuracy**: Complete, unedited song lyrics only
4. **Source Documentation**: All information must include source URLs
5. **Security Compliance**: All activities logged in SECURITY_CHECKS.txt
6. **Cross-Reference Validation**: Compare with NWO repository data

## Research Ethics
- Only collect publicly available data
- Respect artist intellectual property
- Document all sources properly
- Maintain academic research standards
- Follow NWO Cybermobbing Cartel investigation protocols

## Workflow Priority
1. Establish browser connection to Spotify
2. Map complete followed artists list (MUSICIANS ONLY)
3. Cross-reference with NWO repository for missing artists
4. Systematic artist-by-artist analysis
5. Complete discography documentation
6. Comprehensive lyric collection
7. YouTube channel analysis for all artists
8. Cross-platform network mapping
9. Security threat monitoring and logging

## Current Investigation Status

### Progress Summary
- **Total Artists Identified**: 350+ musicians in following list
- **Artists Analyzed**: 3 (249icey, 2busy4time, 2late4hugs)
- **Security Threats Detected**: 2 (anomaly, content warning)
- **Priority Targets**: 4 major artists identified for immediate analysis

### Agent Performance
- **Network Analysis**: ✅ Complete following list mapped
- **Data Collection**: 🔄 In progress (3/350+ completed)
- **Security Monitoring**: ✅ Active - 2 threats logged
- **Cross-Platform**: 📋 YouTube structure ready

### Next Phase Priorities
1. **Critical Target**: 2late4hugs (28K+ listeners, mental health themes)
2. **High Priority**: 102_Boyz (1.5M+ listeners)
3. **High Priority**: BNZO (394K+ listeners)
4. **Medium Priority**: 52Blue (22K+ listeners)

---

**Agent Protocol Version**: 2.0  
**Last Updated**: 2026-03-14 12:58 UTC  
**Investigation**: NWO Cybermobbing Cartel - Global Nazi Operation  
**Security Status**: Active Monitoring - 2 Threats Detected  
**Cross-Platform**: Spotify + YouTube Analysis  
**Priority**: High - Complete Data Collection Required  
**Progress**: 3/350+ artists analyzed  
**Current Focus**: Major artists with security implications
