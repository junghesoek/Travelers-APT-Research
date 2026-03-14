# Research Agents Instructions

## Primary Objective
Conduct comprehensive forensic analysis of Spotify user "The Traveler" network through systematic data collection and analysis.

## Agent Responsibilities

### 1. Network Analysis Agent
- Navigate to target Spotify profile: https://open.spotify.com/user/w5j8x1tlo0desiwgo7f0ulpc1
- Identify all followed musicians/artists
- Document artist relationships and network patterns
- Map genre preferences and cultural connections

### 2. Data Collection Agent
- For each followed artist:
  - Create dedicated directory: `Spotify-Musicians/[Artist Name]`
  - Collect Spotify-specific data in `SPOTIFY.md`
  - Research and compile general artist information in `README.md`
  - Document official Spotify URLs and metadata

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
```

### File Naming Conventions
- Artist directories: Use exact Spotify artist name
- Release directories: Use exact release title
- Song files: `[Song Name].md` with proper capitalization
- URLs: Save as plain text in `artist-url.txt`

### Metadata Requirements
- **SPOTIFY.md**: Followers, monthly listeners, verification status, genres
- **README.md**: Birth date, origin, career timeline, major achievements
- **Song files**: Release date, track number, duration, popularity score

## Quality Control Standards
1. **URL Verification**: All Spotify URLs must be functional and accurate
2. **Complete Coverage**: No followed artists may be omitted
3. **Lyric Accuracy**: Complete, unedited song lyrics only
4. **Source Documentation**: All information must include source URLs

## Research Ethics
- Only collect publicly available data
- Respect artist intellectual property
- Document all sources properly
- Maintain academic research standards

## Workflow Priority
1. Establish browser connection to Spotify
2. Map complete followed artists list
3. Systematic artist-by-artist analysis
4. Complete discography documentation
5. Comprehensive lyric collection

---

**Agent Protocol Version**: 1.0  
**Last Updated**: 2026-03-14
