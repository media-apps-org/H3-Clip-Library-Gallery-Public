# H3 Clip Library — Public Gallery

This repository is the public deployment target for the H3 Clip Library static gallery.

The authoritative source records remain in the private repository:
https://github.com/media-apps-org/H3-Clip-Library

The contents of this repository are generated and published by the private source repository's GitHub Actions workflow. Do not commit private records, unreviewed workflows, local MP4 files, or credentials here.

After the first successful publication, configure GitHub Pages:
- Build and deployment: Deploy from a branch
- Branch: main
- Folder: /(root)

Expected site URL:
https://media-apps-org.github.io/H3-Clip-Library-Gallery-Public/

Publication is opt-in per asset. The source asset must set both publish=true and visibility=public. Only allowlisted metadata and selected artifact files are copied into this public repository.

For operational instructions and security constraints, see:
https://github.com/media-apps-org/H3-Clip-Library/blob/main/docs/PUBLICATION.md
