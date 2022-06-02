# analysis-ntuples
Repository for the lists of ntuples and information contained therein used in the analyses.

## Usage
Clone this repository in your working area
(usually in your Analysis/Tools or Analysis/Ntuplizer projects)

```bash
git clone https://github.com/desy-cms/analysis-ntuples.git data/ntuples
cd data/ntuples
```

In the **analysis-specific** directory tree there is a README.md
with information about the available datasets and two directories,
namely *data* and *mc*, inside which one can find the rootFileList.txt
files for each dataset plus additional info about the ntuple production.

## Recommended ntuples for MSSM Hbb analyses

* RunII Legacy 2017 analysis: [2017/v6](2017/v6)
  * [rootFileLists for data](2017/v6/data)
  * [rootFileLists for monte carlo](2017/v6/mc)
  * Inputs to ntuples:
    * [trigger information](2017/v6/trigger_info.yml)
    * [datasets for data](2017/v6/data/datasets.yml)
    * [datasets for monte carlo](2017/v6/mc/datasets.yml)

:warning: the versioning labels mssmhbb-2017-v4 and mssmhbb-2018-v3 are deprecated and will be removed in the future
