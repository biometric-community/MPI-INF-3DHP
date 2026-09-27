        # MPI-INF-3DHP

        [![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
        [![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FMPI--INF--3DHP-181717?logo=github)](https://github.com/biometric-community/MPI-INF-3DHP)
        [![Access: public](https://img.shields.io/badge/access-public-0e8a16.svg)](http://gvv.mpi-inf.mpg.de/3dhp-dataset/)

        **MPI-INF-3DHP** — multi-view / markerless **3D human pose** dataset from MPI GVV.

        - **Dataset repository**: https://github.com/biometric-community/MPI-INF-3DHP
        - **Upstream source**: http://gvv.mpi-inf.mpg.de/3dhp-dataset/
        - **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
        - **License (data)**: upstream terms — this packaging does **not** relicense the data


        | Field | Value |
        |-------|-------|
        | Catalog id (tbiom) | `mpi-inf-3dhp` |
        | Category | `pose3d` |
        | Access | `public` |
        | Upstream homepage | http://gvv.mpi-inf.mpg.de/3dhp-dataset/ |

        ## TL;DR

        - **Task**: 3D human pose estimation
        - **Access**: **public**
        - **This mirror**: documentation + download helpers only (no bulk payload in git)
        - **Notes**: Multi-part archives from the official MPI page. This mirror ships docs/helpers only.

        ## Table of contents

        - [Download](#download)
        - [Dataset structure](#dataset-structure)
        - [Known issues and caveats](#known-issues-and-caveats)
        - [License](#license)
        - [Citation](#citation)
        - [Contact](#contact)

        ## Download

        ### Clone this repository

        ```bash
        git clone git@github.com:biometric-community/MPI-INF-3DHP.git
        cd MPI-INF-3DHP
        ```

        ### tbiom monorepo helper

        ```bash
        bash projects/datasets/scripts/download_mpi_inf_3dhp.sh
        ```

        Then follow the printed upstream steps and place archives under `projects/datasets/mpi-inf-3dhp/`.

        ## Dataset structure

        ```text
        MPI-INF-3DHP/
        ├── README.md
        ├── LICENSE                 # helpers / docs (CC BY 4.0)
        ├── .gitignore
        └── extracted/              # local only after you download (gitignored)
        ```

        ## Known issues and caveats

        - Upstream hosts / Drive quotas often block fully automated downloads.
        - Do not commit multi-GB payloads to this GitHub mirror.

        ## License

        Helpers/docs: CC BY 4.0. Dataset files: upstream license / access agreement.

        ## Citation

        ```bibtex
        @inproceedings{mehta2017monocular,
  title={Monocular 3D Human Pose Estimation In The Wild Using Improved CNN Supervision},
  author={Mehta, Dushyant and others},
  booktitle={3DV},
  year={2017}
}
        ```

        ## Contact

        - Upstream: http://gvv.mpi-inf.mpg.de/3dhp-dataset/
        - Packaging: https://github.com/biometric-community/MPI-INF-3DHP/issues
