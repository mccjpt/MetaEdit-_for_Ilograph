# MetaEdit+ generator to export models to Ilograph (www.ilograph.com/)

Generator exports a model made with any domain-specific modeling language from MetaEdit+ to IloGraph. 

Restrictions: 
1) Creates one Ilograph perspective that includes subgraphs from MetaEdit+ (by changing generators nested symbols or ports could be applied as own perspectives too).
2) Ilograph does not support n-ary relationships so generators force them to be binary (first role is taken as from role in Ilograph, and as currently language agnostic changing IloOneGraphRelations() allows to treat specifics of particular metamodel
3) Ilograph does not support reuse in different contexts
4) Ilograph does not support subgraps for relationships
5) Translates user given names to legal in Ilograph (: to space, > to (>))

.rep files include MERL generators for MetaEdit+ (www.metacase.com) that can be read into Generator Editor (see https://metacase.com/support/55/manuals/mwb/Mw-5_3_1.html#Heading1542). These can be imported to your language definition (Graph type) or to the main Graph enabling export from all languages already available or that you have created. Genenerators can be freely changed in Generator Editor to detail them fitting to your language (e.g. exclude elements, apply specially your metamodel, like specific behavior or icon, dealing with subgraphs as perspectives, or treat direction of relationships).

MetaEdit+ is a language workbench that allows supporting your modeling language. Tool provides functionality for collaborative modeling, versioning, model checking and publishing goal structures, available at: https://www.metacase.com/download.
