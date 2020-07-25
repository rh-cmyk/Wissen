#source 

# Xin Qian et al., “Beyond ITunes for Papers: Redefining the Unit of Interaction in Literature Review Tools,” in *Conference Companion Publication of the 2019 on Computer Supported Cooperative Work and Social Computing*, CSCW ’19 (Austin, TX, USA: Association for Computing Machinery, 2019), 341–346, https://doi.org/10.1145/3311957.3359455.

"Many commercial (e.g., Mendeley, Zotero) and research literature review tools [11, 21] explicitly or implicitly assume that the paper is the unit of interaction. Functioning like "iTunes for papers", researchers import papers, reason about relationships between papers (e.g., with tags, stars, citation links), annotate papers, and export papers as citations in written literature reviews. [...] We argue that systems should enable researchers to work directly with grounded claims. Grounded claims are concise statements grounded in context that helps a user understand, interpret, judge, and use a claim (see Fig. 1). For example, a claim might be contextualized by its evidence, such as a key figure or experiment details, or related claims that corroborate, oppose, or clarify a focal claim. The provenance of a claim, such as its source collaboration networks, institutional dynamics, and prestige, can be important context for understanding its validity and impact." ([Qian et al 2019:342](zotero://open-pdf/library/items/XI3NC562?page=2))

"The focal claim (A) is explicitly connected to a claim from another study that closely replicates it (B), and implicitly connected to a similar (but not exactly alike) claim (C). Another claim about the amount of reading scientists must do (D) suggests a potential explanation for scientists' reading behaviors. Clicking on a "min/max" button on the context segments toggles whether they are expanded or collapsed (E). If the user needs more information, there is a direct link (F) back to the location surrounding the claim." ([Qian et al 2019:343](zotero://open-pdf/library/items/XI3NC562?page=3))

"Some research systems have been proposed, such as "micropublications" in bioinformatics, but uptake has been limited. [...] the cognitive costs of deciding in advance what details need to be retained as context for future reuse, with costly consequences for downstream task performance if a premature and inaccurate decision is made early on. Also, systems that require high amounts of precision for specifying context during sensemaking may impose unnecessary interaction costs." ([Qian et al 2019:343](zotero://open-pdf/library/items/XI3NC562?page=3))

"In Knowledge Compressor, claims can be grounded by two kinds of context: 1) evidence: claims can be easily linked to one or more "segments" of a source PDF document (e.g., table, figure, methods details, quote) (see Fig. 3) and 2) related claims: claims can be connected (either with explicit links, or implicitly, by spatial proximity) to other claims on our claim canvas, which operates similarly to argument diagramming and modeling software" ([Qian et al 2019:343](zotero://open-pdf/library/items/XI3NC562?page=3))

"Users create claims by selecting a segment of the source document in the reading pane and writing a (re)description of the associated claim. […] Users can adjust "flexibly compressed" context segments. For example, a user can scroll up in the segment to note that evidence for this claim comes from interviews […] and reason about reliability/diversity of evidence, or extract more details about which sections tend to be read for what kinds of tasks to inform design of a system that highlights specific sections for specific tasks." ([Qian et al 2019:344](zotero://open-pdf/library/items/XI3NC562?page=4))

"Unlike conventional annotation, however, these segments are flexible, and can be adjusted/expanded by the reuser, because they are "live slices" of the source PDF (powered by a pdfjs React component)." ([Qian et al 2019:344](zotero://open-pdf/library/items/XI3NC562?page=4))