# 🎵 Accountability Song Builder

A protest song creation tool for documenting constitutional violations with cited sources, built for civic engagement and accountability advocacy.

## Overview

The Accountability Song Builder is an interactive dashboard that helps you:

- **Document constitutional violations** with specific dates, actors, and behaviors
- **Cite sources** (URLs, reports, testimony, filings) for every claim
- **Track evidence** including images and documentation links
- **Generate protest song lyrics** automatically from your research
- **Export your work** as text or JSON for sharing and collaboration

This tool enforces **evidentiary rigor** by requiring citations for every violation, ensuring that protest songs are grounded in documented facts and verifiable sources.

## Features

### 📝 Research & Documentation
- Add violations with amendment/clause references
- Track dates, times, actors involved, and locations
- Capture detailed descriptions of documented behavior
- Attach multiple citations (URLs, reports, testimony)
- Include images (local paths or online URLs)
- Add notes for context and additional details

### 🎵 Live Song Preview
- See your song structure generate in real-time
- Refrain templates with your citations automatically populated
- Call-to-action sections ready for your audience
- Full song preview shows all violations organized by amendment

### 💾 Export & Save Options
- **Export Full Song** - Complete accountability song with all violations
- **Export New Addition Only** - Just the latest violation you added
- **Export as JSON** - Save all your data for backup or sharing
- **Load from JSON** - Restore previous work from a saved file
- **Auto-save** - Your work is automatically saved to browser storage

### 🔄 Edit & Manage
- Edit any violation after adding it
- Delete violations that need correction
- Reorganize your violations by amendment
- Clear all data and start fresh

## How It Works

### Song Structure Template

Each violation generates a song section following this pattern:

```
CHORUS
[Amendment Number] Amendment Time

REFRAIN
[date/time], [actors] at [location].
This violates [Amendment].
Sources: [citations]

CALL TO ACTION
call your rep. call your sen.
you know what to do,
[Amendment] Amendment Time.
whoao ooh oah ooh
[Amendment] amendment time.
```

### Cited Sources in Action

When you add a violation with citations like:
- Congressional testimony
- News reporting (Reuters, AP, Washington Post, etc.)
- Court filings or legal documents
- Government records or data
- Investigative journalism pieces

They appear in your exported song, making it easy for listeners to verify claims themselves.

## Getting Started

### Installation

1. Download `protest_song_dashboard.html`
2. Open it in any modern web browser (Chrome, Firefox, Safari, Edge)
3. Start adding violations

**No server, no installation, no dependencies** — everything runs locally in your browser.

### Basic Workflow

1. **Research** a constitutional violation in the news
2. **Fill the form** with details and citations
3. **See preview** update in real-time on the right panel
4. **Add more violations** to build out your full song
5. **Export** when you're ready to share or perform

### Example: Starting Your First Violation

**Amendment/Clause:** 25th Amendment  
**Date:** 2021-01-06  
**Actors:** Donald Trump, Proud Boys, Steve Bannon  
**Behavior:** Called on armed groups to march to Capitol; refused to act to stop violence for hours  
**Location:** U.S. Capitol, Washington D.C.  
**Citations:**
- https://www.congress.gov/118/hearing/january-6-committee-reports
- https://www.justice.gov/capitol-breach
- Washington Post article on Jan 6 events

## Data Storage

### Browser Storage
- Your violations are saved automatically to browser local storage
- Data persists between browser sessions
- No account or login required

### Export & Backup
- **Export as JSON** to back up your work
- **Export as Text** to share or perform
- **Load from JSON** to restore previous sessions

## Amendment Reference

The tool works with any amendment or constitutional clause. Common ones include:

- **25th Amendment** - Presidential succession and incapacity
- **Emoluments Clause** (Article II, Section 1, Clause 7) - Foreign payments prohibition
- **14th Amendment Section 3** - Disqualification for insurrection
- **1st Amendment** - Free speech, assembly
- **4th Amendment** - Unreasonable searches and seizures
- **5th Amendment** - Due process, self-incrimination
- And any other constitutional provision

## Citation Standards

For accountability to work, citations must be:

- **Specific** - Link to actual reporting, testimony, or filings
- **Verifiable** - Reader can check the source themselves
- **Credible** - From established news outlets, government records, or court filings
- **Dated** - Include when the reporting or testimony occurred

### Strong Citation Examples
- Congressional committee hearing transcripts
- Department of Justice charging documents
- Major news outlet reporting (Reuters, AP, Washington Post, NYT, etc.)
- Court filings and judicial records
- Government agency reports and data
- Investigative journalism (ProPublica, Center for Investigative Reporting, etc.)

### Weak Citation Examples
- Unattributed claims
- Social media posts without sources
- Speculation or opinion without facts
- Vague references to "reports"

## Use Cases

### Protest Organization
Build songs for mass demonstrations with verifiable claims that withstand scrutiny.

### Educational Tool
Teach civic engagement by combining music with constitutional law and source verification.

### Political Advocacy
Create accountability content grounded in documented facts and evidence.

### Collaborative Songwriting
Export JSON, share with others, have them add violations, and merge the data back.

## File Format: JSON Export

Your exported JSON follows this structure:

```json
{
  "exportDate": "2026-01-19T12:34:56.789Z",
  "violations": [
    {
      "id": 1705682096789,
      "amendment": "25th Amendment",
      "date": "2021-01-06",
      "time": "13:00",
      "actors": "Donald Trump, Proud Boys, Steve Bannon",
      "behavior": "Called on armed groups to march to Capitol...",
      "location": "U.S. Capitol, Washington D.C.",
      "citations": [
        "https://www.congress.gov/118/hearing/january-6-committee-reports",
        "https://www.justice.gov/capitol-breach"
      ],
      "images": [],
      "notes": "Additional context here"
    }
  ]
}
```

## Browser Compatibility

Works on all modern browsers:
- Chrome/Chromium (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

Requires JavaScript enabled.

## Privacy

- **All data stays local** - Nothing is sent to servers
- **No tracking** - No analytics or cookies
- **Your control** - You decide when to export or share
- **Easy deletion** - Clear all data with one click

## Performance

- Handles 50+ violations smoothly
- Instant preview updates
- Fast export/import
- Minimal memory footprint

## Tips & Best Practices

### Research Workflow
1. When you see a news story about potential constitutional violation, open the dashboard
2. Fill out the form with what you've confirmed from the reporting
3. Add citations as you go
4. Revisit and edit as more information emerges
5. Keep a JSON backup of your work

### Citation Tips
- Copy full URLs so people can click directly
- Include specific page or section references
- Date your citations (e.g., "Washington Post, Jan 15, 2021")
- Link to primary sources when possible (court filings, testimony)

### Song Performance
- The chorus is memorable and singable — people will remember it
- The specific details in refrains ground the song in reality
- Listeners can fact-check claims on the spot
- Ad-libbed additions from the crowd become part of the music

### Collaboration
- Export JSON and share via email or cloud storage
- Others can load your JSON and add their own violations
- Merge different versions by copying violations
- Build a comprehensive accountability song together

## Limitations & Notes

- Data is stored per-browser (clearing cache will clear data)
- For permanent backup, export JSON regularly
- Image paths need to be accessible (local file paths work from the same device)
- No real-time collaboration (use JSON files to share versions)

## Future Enhancements

Possible additions (feel free to fork and implement):
- Cloud storage option for collaboration
- Multi-user support
- Integration with fact-checking APIs
- MIDI/audio generation for the song
- Sharing and performance tracking
- Amendment-specific templates
- Social media export

## Contributing

This is a civic tool created to support accountability advocacy. If you want to:
- Fix bugs
- Add features
- Improve documentation
- Translate to other languages
- Create derivative tools

Feel free to fork, modify, and share back.

## License

This tool is provided as-is for civic engagement and educational purposes. Use it freely.

## Support

If you encounter issues:
1. Check that JavaScript is enabled in your browser
2. Try clearing browser cache and reloading
3. Ensure your citations are properly formatted URLs
4. Export your JSON data regularly as backup
5. Test in a different browser if problems persist

## About

Built to support informed civic engagement through documented protest and accountability advocacy. The tool enforces citation of sources to ensure that protest songs are grounded in verifiable facts, not speculation.

**Core Principle:** If you're going to claim a constitutional violation happened, show your work. Cite the sources. Make it verifiable.

---

**Questions or feedback?** The tool is designed to be transparent and auditable — if something feels wrong, it probably is. Check your sources, verify your claims, cite everything.

🎵 Build accountability. Sing truth. Cite sources. 🎵
