# Knwoledge Graph Construction Tools
Description of the tools for knowledge graph construction

## Tool X (TEMPLATE):
- **Name of the tool**:
- **Description**:
- **Repository (link to the tool’s repository)**:
- **Website (if is different to the repository)**;
- **Open source? (If not open sourced, ideally provide an option to test it)**:
- **Year introduced**:
- **Contact person (who is the main contact person?)**:
- **Purpose (what can one do with the tool?)**: Select one of this options: Processor (executes rules to generate a knowledge graph), editor (automatically o manually generation of mapping rules), other (e.g., pre-processing)
- **Mapping language**: (which mapping language(s) is supported by the tool)
- **Supported data (formats, sizes)**:
- **Programming language**:
- **Special features**:
- **DOI**:
- **License**:
- **Test cases**: (if any for the supported languages)
- **Related use cases**: (specify use cases shared with the community group (if any) where the tool is used)
- **Related projects**: (specify projects (if any) where the tool is used, ideally provide links to the projects descriptions)


## Tool 1:
- **Name of the tool**: Morph-CSV
- **Description**: Morph-CSV is an open source tool for querying tabular data sources using SPARQL. It exploits the information from the query, RML+FnO mappings and CSVW metadata to enhance the performance and completness of traditional OBDA systems (SPARQL-to-SQL translators). At this moment can be embebed in the top of any R2RML-compliant system.
- **Repository**: https://github.com/oeg-upm/morph-csv
- **Website**: https://morph.oeg.fi.upm.es/tool/morph-csv
- **Open source**: Yes
- **Year introduced**: 2019
- **Contact person**: David Chaves (dchaves@fi.upm.es)
- **Purpose**: Other (Enhance SPARQL-to-SQL engines when data is in CSV)
- **Mapping language**: YARRRML+FnO and CSVW
- **Supported data**: CSV (tested with BSBM 360K products)
- **Programming language**: Python + Bash
- **DOI**: https://doi.org/10.5281/zenodo.3731941
- **License**: Apache-2.0
- **Related use cases**: https://github.com/kg-construct/use-cases/blob/master/oeg-publictransport.md
- **Related projects**: http://sprint-transport.eu/

## Tool 2:
- **Name of the tool**: RMLEditor
- **Description**: The RMLEditor offers a graphical user interface to create rules to generate knowledge graphs based on heterogeneous data sources.
- **Repository (link to the tool’s repository)**: https://github.com/RMLio/rmleditor-ce
- **Website (if is different to the repository)**: https://app.rml.io/rmleditor/
- **Open source? (If not open sourced, ideally provide an option to test it)**: No
- **Year introduced**: 2016
- **Contact person (who is the main contact person?)**: Pieter Heyvaert (pieter.heyvaert@ugent.be)
- **Purpose (what can one do with the tool?)**: editor
- **Mapping language**: [R2]RML
- **Supported data (formats, sizes)**: CSV, JSON, XML
- **Programming language**: HTML/CSS/JS
- **Special features**: Uses LOV to find relevant classes and properties. Uses MapVOWL to visualize rules.
- **DOI**: N/A
- **License**: Free community edition with limitations and paid edition without limitations. 
- **Test cases**: None
- **Related use cases**: None
- **Related projects**: [DyVerSIFy](https://www.imec-int.com/en/what-we-offer/research-portfolio/dyversify), [MOS2S](https://www.mos2s.eu/), [COMBUST](https://www.imec-int.com/en/what-we-offer/research-portfolio/combust)
