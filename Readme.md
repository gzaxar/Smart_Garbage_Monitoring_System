***4ο Δημοτικό Σχολείο Καλαμαριάς***

**Smart Garbage Monitoring System**


<html xmlns:v="urn:schemas-microsoft-com:vml"
xmlns:o="urn:schemas-microsoft-com:office:office"
xmlns:w="urn:schemas-microsoft-com:office:word"
xmlns:m="http://schemas.microsoft.com/office/2004/12/omml"
xmlns="http://www.w3.org/TR/REC-html40">

<head>
<meta http-equiv=Content-Type content="text/html; charset=windows-1253">
<meta name=ProgId content=Word.Document>
<meta name=Generator content="Microsoft Word 15">
<meta name=Originator content="Microsoft Word 15">
<link rel=File-List
href="Arduino_smart_garbadge_monitoring_system_2023_Readme1.files/filelist.xml">
<link rel=Edit-Time-Data
href="Arduino_smart_garbadge_monitoring_system_2023_Readme1.files/editdata.mso">
<!--[if !mso]>
 <![endif]--><!--[if gte mso 9]><xml>
 <o:DocumentProperties>
  <o:Author>PC19</o:Author>
  <o:LastAuthor>Γεώργιος Ζαχαριάδης</o:LastAuthor>
  <o:Revision>2</o:Revision>
  <o:TotalTime>44</o:TotalTime>
  <o:Created>2023-06-17T17:42:00Z</o:Created>
  <o:LastSaved>2023-06-17T17:42:00Z</o:LastSaved>
  <o:Pages>1</o:Pages>
  <o:Words>1179</o:Words>
  <o:Characters>6370</o:Characters>
  <o:Lines>53</o:Lines>
  <o:Paragraphs>15</o:Paragraphs>
  <o:CharactersWithSpaces>7534</o:CharactersWithSpaces>
  <o:Version>16.00</o:Version>
 </o:DocumentProperties>
 <o:OfficeDocumentSettings>
  <o:AllowPNG/>
 </o:OfficeDocumentSettings>
</xml><![endif]-->
<link rel=dataStoreItem
href="Arduino_smart_garbadge_monitoring_system_2023_Readme1.files/item0001.xml"
target="Arduino_smart_garbadge_monitoring_system_2023_Readme1.files/props002.xml">
<link rel=themeData
href="Arduino_smart_garbadge_monitoring_system_2023_Readme1.files/themedata.thmx">
<link rel=colorSchemeMapping
href="Arduino_smart_garbadge_monitoring_system_2023_Readme1.files/colorschememapping.xml">
<!--[if gte mso 9]><xml>
 <w:WordDocument>
  <w:SpellingState>Clean</w:SpellingState>
  <w:TrackMoves>false</w:TrackMoves>
  <w:TrackFormatting/>
  <w:PunctuationKerning/>
  <w:ValidateAgainstSchemas/>
  <w:SaveIfXMLInvalid>false</w:SaveIfXMLInvalid>
  <w:IgnoreMixedContent>false</w:IgnoreMixedContent>
  <w:AlwaysShowPlaceholderText>false</w:AlwaysShowPlaceholderText>
  <w:DoNotPromoteQF/>
  <w:LidThemeOther>EL</w:LidThemeOther>
  <w:LidThemeAsian>ZH-CN</w:LidThemeAsian>
  <w:LidThemeComplexScript>X-NONE</w:LidThemeComplexScript>
  <w:Compatibility>
   <w:BreakWrappedTables/>
   <w:SnapToGridInCell/>
   <w:WrapTextWithPunct/>
   <w:UseAsianBreakRules/>
   <w:DontGrowAutofit/>
   <w:SplitPgBreakAndParaMark/>
   <w:EnableOpenTypeKerning/>
   <w:DontFlipMirrorIndents/>
   <w:OverrideTableStyleHps/>
   <w:UseFELayout/>
  </w:Compatibility>
  <m:mathPr>
   <m:mathFont m:val="Cambria Math"/>
   <m:brkBin m:val="before"/>
   <m:brkBinSub m:val="&#45;-"/>
   <m:smallFrac m:val="off"/>
   <m:dispDef/>
   <m:lMargin m:val="0"/>
   <m:rMargin m:val="0"/>
   <m:defJc m:val="centerGroup"/>
   <m:wrapIndent m:val="1440"/>
   <m:intLim m:val="subSup"/>
   <m:naryLim m:val="undOvr"/>
  </m:mathPr></w:WordDocument>
</xml><![endif]--><!--[if gte mso 9]><xml>
 <w:LatentStyles DefLockedState="false" DefUnhideWhenUsed="false"
  DefSemiHidden="false" DefQFormat="false" DefPriority="99"
  LatentStyleCount="375">
  <w:LsdException Locked="false" Priority="0" QFormat="true" Name="Normal"/>
  <w:LsdException Locked="false" Priority="9" QFormat="true" Name="heading 1"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 2"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 3"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 4"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 5"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 6"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 7"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 8"/>
  <w:LsdException Locked="false" Priority="9" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="heading 9"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 6"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 7"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 8"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index 9"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 1"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 2"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 3"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 4"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 5"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 6"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 7"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 8"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" Name="toc 9"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Normal Indent"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="footnote text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="annotation text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="header"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="footer"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="index heading"/>
  <w:LsdException Locked="false" Priority="35" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="caption"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="table of figures"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="envelope address"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="envelope return"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="footnote reference"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="annotation reference"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="line number"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="page number"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="endnote reference"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="endnote text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="table of authorities"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="macro"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="toa heading"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Bullet 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Number 5"/>
  <w:LsdException Locked="false" Priority="10" QFormat="true" Name="Title"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Closing"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Signature"/>
  <w:LsdException Locked="false" Priority="1" SemiHidden="true"
   UnhideWhenUsed="true" Name="Default Paragraph Font"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text Indent"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="List Continue 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Message Header"/>
  <w:LsdException Locked="false" Priority="11" QFormat="true" Name="Subtitle"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Salutation"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Date"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text First Indent"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text First Indent 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Note Heading"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text Indent 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Body Text Indent 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Block Text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Hyperlink"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="FollowedHyperlink"/>
  <w:LsdException Locked="false" Priority="22" QFormat="true" Name="Strong"/>
  <w:LsdException Locked="false" Priority="20" QFormat="true" Name="Emphasis"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Document Map"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Plain Text"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="E-mail Signature"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Top of Form"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Bottom of Form"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Normal (Web)"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Acronym"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Address"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Cite"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Code"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Definition"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Keyboard"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Preformatted"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Sample"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Typewriter"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="HTML Variable"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Normal Table"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="annotation subject"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="No List"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Outline List 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Outline List 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Outline List 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Simple 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Simple 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Simple 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Classic 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Classic 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Classic 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Classic 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Colorful 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Colorful 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Colorful 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Columns 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 6"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 7"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Grid 8"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 4"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 5"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 6"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 7"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table List 8"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table 3D effects 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table 3D effects 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table 3D effects 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Contemporary"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Elegant"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Professional"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Subtle 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Subtle 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Web 1"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Web 2"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Web 3"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Balloon Text"/>
  <w:LsdException Locked="false" Priority="39" Name="Table Grid"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Table Theme"/>
  <w:LsdException Locked="false" SemiHidden="true" Name="Placeholder Text"/>
  <w:LsdException Locked="false" Priority="1" QFormat="true" Name="No Spacing"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 1"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 1"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 1"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 1"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 1"/>
  <w:LsdException Locked="false" SemiHidden="true" Name="Revision"/>
  <w:LsdException Locked="false" Priority="34" QFormat="true"
   Name="List Paragraph"/>
  <w:LsdException Locked="false" Priority="29" QFormat="true" Name="Quote"/>
  <w:LsdException Locked="false" Priority="30" QFormat="true"
   Name="Intense Quote"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 1"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 1"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 1"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 1"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 1"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 1"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 2"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 2"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 2"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 2"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 2"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 2"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 2"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 2"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 2"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 2"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 2"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 3"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 3"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 3"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 3"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 3"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 3"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 3"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 3"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 3"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 3"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 3"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 4"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 4"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 4"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 4"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 4"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 4"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 4"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 4"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 4"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 4"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 4"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 5"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 5"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 5"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 5"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 5"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 5"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 5"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 5"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 5"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 5"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 5"/>
  <w:LsdException Locked="false" Priority="60" Name="Light Shading Accent 6"/>
  <w:LsdException Locked="false" Priority="61" Name="Light List Accent 6"/>
  <w:LsdException Locked="false" Priority="62" Name="Light Grid Accent 6"/>
  <w:LsdException Locked="false" Priority="63" Name="Medium Shading 1 Accent 6"/>
  <w:LsdException Locked="false" Priority="64" Name="Medium Shading 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="65" Name="Medium List 1 Accent 6"/>
  <w:LsdException Locked="false" Priority="66" Name="Medium List 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="67" Name="Medium Grid 1 Accent 6"/>
  <w:LsdException Locked="false" Priority="68" Name="Medium Grid 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="69" Name="Medium Grid 3 Accent 6"/>
  <w:LsdException Locked="false" Priority="70" Name="Dark List Accent 6"/>
  <w:LsdException Locked="false" Priority="71" Name="Colorful Shading Accent 6"/>
  <w:LsdException Locked="false" Priority="72" Name="Colorful List Accent 6"/>
  <w:LsdException Locked="false" Priority="73" Name="Colorful Grid Accent 6"/>
  <w:LsdException Locked="false" Priority="19" QFormat="true"
   Name="Subtle Emphasis"/>
  <w:LsdException Locked="false" Priority="21" QFormat="true"
   Name="Intense Emphasis"/>
  <w:LsdException Locked="false" Priority="31" QFormat="true"
   Name="Subtle Reference"/>
  <w:LsdException Locked="false" Priority="32" QFormat="true"
   Name="Intense Reference"/>
  <w:LsdException Locked="false" Priority="33" QFormat="true" Name="Book Title"/>
  <w:LsdException Locked="false" Priority="37" SemiHidden="true"
   UnhideWhenUsed="true" Name="Bibliography"/>
  <w:LsdException Locked="false" Priority="39" SemiHidden="true"
   UnhideWhenUsed="true" QFormat="true" Name="TOC Heading"/>
  <w:LsdException Locked="false" Priority="41" Name="Plain Table 1"/>
  <w:LsdException Locked="false" Priority="42" Name="Plain Table 2"/>
  <w:LsdException Locked="false" Priority="43" Name="Plain Table 3"/>
  <w:LsdException Locked="false" Priority="44" Name="Plain Table 4"/>
  <w:LsdException Locked="false" Priority="45" Name="Plain Table 5"/>
  <w:LsdException Locked="false" Priority="40" Name="Grid Table Light"/>
  <w:LsdException Locked="false" Priority="46" Name="Grid Table 1 Light"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark"/>
  <w:LsdException Locked="false" Priority="51" Name="Grid Table 6 Colorful"/>
  <w:LsdException Locked="false" Priority="52" Name="Grid Table 7 Colorful"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 1"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 1"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 1"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 1"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 1"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 1"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 2"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 2"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 2"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 2"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 2"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 2"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 3"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 3"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 3"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 3"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 3"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 3"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 4"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 4"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 4"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 4"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 4"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 4"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 5"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 5"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 5"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 5"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 5"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 5"/>
  <w:LsdException Locked="false" Priority="46"
   Name="Grid Table 1 Light Accent 6"/>
  <w:LsdException Locked="false" Priority="47" Name="Grid Table 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="48" Name="Grid Table 3 Accent 6"/>
  <w:LsdException Locked="false" Priority="49" Name="Grid Table 4 Accent 6"/>
  <w:LsdException Locked="false" Priority="50" Name="Grid Table 5 Dark Accent 6"/>
  <w:LsdException Locked="false" Priority="51"
   Name="Grid Table 6 Colorful Accent 6"/>
  <w:LsdException Locked="false" Priority="52"
   Name="Grid Table 7 Colorful Accent 6"/>
  <w:LsdException Locked="false" Priority="46" Name="List Table 1 Light"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark"/>
  <w:LsdException Locked="false" Priority="51" Name="List Table 6 Colorful"/>
  <w:LsdException Locked="false" Priority="52" Name="List Table 7 Colorful"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 1"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 1"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 1"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 1"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 1"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 1"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 1"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 2"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 2"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 2"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 2"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 2"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 2"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 2"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 3"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 3"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 3"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 3"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 3"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 3"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 3"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 4"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 4"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 4"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 4"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 4"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 4"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 4"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 5"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 5"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 5"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 5"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 5"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 5"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 5"/>
  <w:LsdException Locked="false" Priority="46"
   Name="List Table 1 Light Accent 6"/>
  <w:LsdException Locked="false" Priority="47" Name="List Table 2 Accent 6"/>
  <w:LsdException Locked="false" Priority="48" Name="List Table 3 Accent 6"/>
  <w:LsdException Locked="false" Priority="49" Name="List Table 4 Accent 6"/>
  <w:LsdException Locked="false" Priority="50" Name="List Table 5 Dark Accent 6"/>
  <w:LsdException Locked="false" Priority="51"
   Name="List Table 6 Colorful Accent 6"/>
  <w:LsdException Locked="false" Priority="52"
   Name="List Table 7 Colorful Accent 6"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Mention"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Smart Hyperlink"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Hashtag"/>
  <w:LsdException Locked="false" SemiHidden="true" UnhideWhenUsed="true"
   Name="Unresolved Mention"/>
 </w:LatentStyles>
</xml><![endif]-->
<style>
<!--
 /* Font Definitions */
 @font-face
	{font-family:Helvetica;
	panose-1:2 11 6 4 2 2 2 2 2 4;
	mso-font-charset:161;
	mso-generic-font-family:swiss;
	mso-font-pitch:variable;
	mso-font-signature:-536858881 -1073711013 9 0 511 0;}
@font-face
	{font-family:Wingdings;
	panose-1:5 0 0 0 0 0 0 0 0 0;
	mso-font-charset:2;
	mso-generic-font-family:auto;
	mso-font-pitch:variable;
	mso-font-signature:0 268435456 0 0 -2147483648 0;}
@font-face
	{font-family:SimSun;
	panose-1:2 1 6 0 3 1 1 1 1 1;
	mso-font-alt:\5B8B\4F53;
	mso-font-charset:134;
	mso-generic-font-family:auto;
	mso-font-pitch:variable;
	mso-font-signature:3 680460288 22 0 262145 0;}
@font-face
	{font-family:"Cambria Math";
	panose-1:2 4 5 3 5 4 6 3 2 4;
	mso-font-charset:0;
	mso-generic-font-family:roman;
	mso-font-pitch:variable;
	mso-font-signature:3 0 0 0 1 0;}
@font-face
	{font-family:DengXian;
	panose-1:2 1 6 0 3 1 1 1 1 1;
	mso-font-alt:\7B49\7EBF;
	mso-font-charset:134;
	mso-generic-font-family:auto;
	mso-font-pitch:variable;
	mso-font-signature:-1610612033 953122042 22 0 262159 0;}
@font-face
	{font-family:Calibri;
	panose-1:2 15 5 2 2 2 4 3 2 4;
	mso-font-charset:161;
	mso-generic-font-family:swiss;
	mso-font-pitch:variable;
	mso-font-signature:-469750017 -1040178053 9 0 511 0;}
@font-face
	{font-family:"Calibri Light";
	panose-1:2 15 3 2 2 2 4 3 2 4;
	mso-font-charset:161;
	mso-generic-font-family:swiss;
	mso-font-pitch:variable;
	mso-font-signature:-469750017 -1040178053 9 0 511 0;}
@font-face
	{font-family:"DengXian Light";
	mso-font-alt:"\7B49\7EBF Light";
	mso-font-charset:134;
	mso-generic-font-family:auto;
	mso-font-pitch:variable;
	mso-font-signature:-1610612033 953122042 22 0 262159 0;}
@font-face
	{font-family:Tahoma;
	panose-1:2 11 6 4 3 5 4 4 2 4;
	mso-font-charset:0;
	mso-generic-font-family:swiss;
	mso-font-pitch:variable;
	mso-font-signature:-520081665 -1073717157 41 0 66047 0;}
@font-face
	{font-family:"Comic Sans MS";
	panose-1:3 15 7 2 3 3 2 2 2 4;
	mso-font-charset:161;
	mso-generic-font-family:script;
	mso-font-pitch:variable;
	mso-font-signature:647 19 0 0 159 0;}
@font-face
	{font-family:"Segoe UI";
	panose-1:2 11 5 2 4 2 4 2 2 3;
	mso-font-charset:161;
	mso-generic-font-family:swiss;
	mso-font-pitch:variable;
	mso-font-signature:-469750017 -1073683329 9 0 511 0;}
@font-face
	{font-family:"\@DengXian Light";
	mso-font-charset:134;
	mso-generic-font-family:auto;
	mso-font-pitch:variable;
	mso-font-signature:-1610612033 953122042 22 0 262159 0;}
@font-face
	{font-family:"\@SimSun";
	panose-1:2 1 6 0 3 1 1 1 1 1;
	mso-font-charset:134;
	mso-generic-font-family:auto;
	mso-font-pitch:variable;
	mso-font-signature:515 680460288 22 0 262145 0;}
@font-face
	{font-family:"\@DengXian";
	panose-1:2 1 6 0 3 1 1 1 1 1;
	mso-font-charset:134;
	mso-generic-font-family:auto;
	mso-font-pitch:variable;
	mso-font-signature:-1610612033 953122042 22 0 262159 0;}
 /* Style Definitions */
 p.MsoNormal, li.MsoNormal, div.MsoNormal
	{mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-parent:"";
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:8.0pt;
	margin-left:0cm;
	line-height:107%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:SimSun;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-fareast-language:EN-US;}
h1
	{mso-style-priority:9;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-link:"Επικεφαλίδα 1 Char";
	mso-style-next:Βασικό;
	margin-top:12.0pt;
	margin-right:0cm;
	margin-bottom:0cm;
	margin-left:0cm;
	margin-bottom:.0001pt;
	line-height:107%;
	mso-pagination:widow-orphan lines-together;
	page-break-after:avoid;
	mso-outline-level:1;
	font-size:16.0pt;
	font-family:"Calibri Light",sans-serif;
	mso-ascii-font-family:"Calibri Light";
	mso-ascii-theme-font:major-latin;
	mso-fareast-font-family:"DengXian Light";
	mso-fareast-theme-font:major-fareast;
	mso-hansi-font-family:"Calibri Light";
	mso-hansi-theme-font:major-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:major-bidi;
	color:#2E74B5;
	mso-themecolor:accent1;
	mso-themeshade:191;
	mso-font-kerning:0pt;
	mso-fareast-language:EN-US;
	font-weight:normal;}
h2
	{mso-style-priority:9;
	mso-style-qformat:yes;
	mso-style-link:"Επικεφαλίδα 2 Char";
	mso-style-next:Βασικό;
	margin-top:2.0pt;
	margin-right:0cm;
	margin-bottom:0cm;
	margin-left:0cm;
	margin-bottom:.0001pt;
	line-height:107%;
	mso-pagination:widow-orphan lines-together;
	page-break-after:avoid;
	mso-outline-level:2;
	font-size:13.0pt;
	font-family:"Calibri Light",sans-serif;
	mso-ascii-font-family:"Calibri Light";
	mso-ascii-theme-font:major-latin;
	mso-fareast-font-family:"DengXian Light";
	mso-fareast-theme-font:major-fareast;
	mso-hansi-font-family:"Calibri Light";
	mso-hansi-theme-font:major-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:major-bidi;
	color:#2E74B5;
	mso-themecolor:accent1;
	mso-themeshade:191;
	mso-fareast-language:EN-US;
	font-weight:normal;}
p.MsoToc1, li.MsoToc1, div.MsoToc1
	{mso-style-update:auto;
	mso-style-priority:39;
	mso-style-next:Βασικό;
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:5.0pt;
	margin-left:0cm;
	line-height:107%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:SimSun;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-fareast-language:EN-US;}
p.MsoHeader, li.MsoHeader, div.MsoHeader
	{mso-style-priority:99;
	mso-style-link:"Κεφαλίδα Char";
	margin:0cm;
	margin-bottom:.0001pt;
	mso-pagination:widow-orphan;
	tab-stops:center 207.65pt right 415.3pt;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:SimSun;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-fareast-language:EN-US;}
p.MsoFooter, li.MsoFooter, div.MsoFooter
	{mso-style-priority:99;
	mso-style-link:"Υποσέλιδο Char";
	margin:0cm;
	margin-bottom:.0001pt;
	mso-pagination:widow-orphan;
	tab-stops:center 207.65pt right 415.3pt;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:SimSun;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-fareast-language:EN-US;}
p.MsoTitle, li.MsoTitle, div.MsoTitle
	{mso-style-priority:10;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-link:"Τίτλος Char";
	mso-style-next:Βασικό;
	margin:0cm;
	margin-bottom:.0001pt;
	mso-add-space:auto;
	mso-pagination:widow-orphan;
	font-size:28.0pt;
	font-family:"Calibri Light",sans-serif;
	mso-ascii-font-family:"Calibri Light";
	mso-ascii-theme-font:major-latin;
	mso-fareast-font-family:"DengXian Light";
	mso-fareast-theme-font:major-fareast;
	mso-hansi-font-family:"Calibri Light";
	mso-hansi-theme-font:major-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:major-bidi;
	letter-spacing:-.5pt;
	mso-font-kerning:14.0pt;
	mso-fareast-language:EN-US;}
p.MsoTitleCxSpFirst, li.MsoTitleCxSpFirst, div.MsoTitleCxSpFirst
	{mso-style-priority:10;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-link:"Τίτλος Char";
	mso-style-next:Βασικό;
	mso-style-type:export-only;
	margin:0cm;
	margin-bottom:.0001pt;
	mso-add-space:auto;
	mso-pagination:widow-orphan;
	font-size:28.0pt;
	font-family:"Calibri Light",sans-serif;
	mso-ascii-font-family:"Calibri Light";
	mso-ascii-theme-font:major-latin;
	mso-fareast-font-family:"DengXian Light";
	mso-fareast-theme-font:major-fareast;
	mso-hansi-font-family:"Calibri Light";
	mso-hansi-theme-font:major-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:major-bidi;
	letter-spacing:-.5pt;
	mso-font-kerning:14.0pt;
	mso-fareast-language:EN-US;}
p.MsoTitleCxSpMiddle, li.MsoTitleCxSpMiddle, div.MsoTitleCxSpMiddle
	{mso-style-priority:10;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-link:"Τίτλος Char";
	mso-style-next:Βασικό;
	mso-style-type:export-only;
	margin:0cm;
	margin-bottom:.0001pt;
	mso-add-space:auto;
	mso-pagination:widow-orphan;
	font-size:28.0pt;
	font-family:"Calibri Light",sans-serif;
	mso-ascii-font-family:"Calibri Light";
	mso-ascii-theme-font:major-latin;
	mso-fareast-font-family:"DengXian Light";
	mso-fareast-theme-font:major-fareast;
	mso-hansi-font-family:"Calibri Light";
	mso-hansi-theme-font:major-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:major-bidi;
	letter-spacing:-.5pt;
	mso-font-kerning:14.0pt;
	mso-fareast-language:EN-US;}
p.MsoTitleCxSpLast, li.MsoTitleCxSpLast, div.MsoTitleCxSpLast
	{mso-style-priority:10;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-link:"Τίτλος Char";
	mso-style-next:Βασικό;
	mso-style-type:export-only;
	margin:0cm;
	margin-bottom:.0001pt;
	mso-add-space:auto;
	mso-pagination:widow-orphan;
	font-size:28.0pt;
	font-family:"Calibri Light",sans-serif;
	mso-ascii-font-family:"Calibri Light";
	mso-ascii-theme-font:major-latin;
	mso-fareast-font-family:"DengXian Light";
	mso-fareast-theme-font:major-fareast;
	mso-hansi-font-family:"Calibri Light";
	mso-hansi-theme-font:major-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:major-bidi;
	letter-spacing:-.5pt;
	mso-font-kerning:14.0pt;
	mso-fareast-language:EN-US;}
a:link, span.MsoHyperlink
	{mso-style-priority:99;
	color:#0563C1;
	mso-themecolor:hyperlink;
	text-decoration:underline;
	text-underline:single;}
a:visited, span.MsoHyperlinkFollowed
	{mso-style-noshow:yes;
	mso-style-priority:99;
	color:#954F72;
	mso-themecolor:followedhyperlink;
	text-decoration:underline;
	text-underline:single;}
p
	{mso-style-priority:99;
	mso-margin-top-alt:auto;
	margin-right:0cm;
	mso-margin-bottom-alt:auto;
	margin-left:0cm;
	mso-pagination:widow-orphan;
	font-size:12.0pt;
	font-family:"Times New Roman",serif;
	mso-fareast-font-family:"Times New Roman";
	mso-fareast-language:ZH-CN;}
p.MsoAcetate, li.MsoAcetate, div.MsoAcetate
	{mso-style-noshow:yes;
	mso-style-priority:99;
	mso-style-link:"Κείμενο πλαισίου Char";
	margin:0cm;
	margin-bottom:.0001pt;
	mso-pagination:widow-orphan;
	font-size:8.0pt;
	font-family:"Tahoma",sans-serif;
	mso-fareast-font-family:SimSun;
	mso-fareast-language:EN-US;}
p.MsoListParagraph, li.MsoListParagraph, div.MsoListParagraph
	{mso-style-priority:34;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:8.0pt;
	margin-left:36.0pt;
	mso-add-space:auto;
	line-height:107%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:SimSun;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-fareast-language:EN-US;}
p.MsoListParagraphCxSpFirst, li.MsoListParagraphCxSpFirst, div.MsoListParagraphCxSpFirst
	{mso-style-priority:34;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-type:export-only;
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:0cm;
	margin-left:36.0pt;
	margin-bottom:.0001pt;
	mso-add-space:auto;
	line-height:107%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:SimSun;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-fareast-language:EN-US;}
p.MsoListParagraphCxSpMiddle, li.MsoListParagraphCxSpMiddle, div.MsoListParagraphCxSpMiddle
	{mso-style-priority:34;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-type:export-only;
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:0cm;
	margin-left:36.0pt;
	margin-bottom:.0001pt;
	mso-add-space:auto;
	line-height:107%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:SimSun;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-fareast-language:EN-US;}
p.MsoListParagraphCxSpLast, li.MsoListParagraphCxSpLast, div.MsoListParagraphCxSpLast
	{mso-style-priority:34;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	mso-style-type:export-only;
	margin-top:0cm;
	margin-right:0cm;
	margin-bottom:8.0pt;
	margin-left:36.0pt;
	mso-add-space:auto;
	line-height:107%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:SimSun;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-fareast-language:EN-US;}
span.MsoSubtleEmphasis
	{mso-style-priority:19;
	mso-style-unhide:no;
	mso-style-qformat:yes;
	color:#404040;
	mso-themecolor:text1;
	mso-themetint:191;
	font-style:italic;}
p.MsoTocHeading, li.MsoTocHeading, div.MsoTocHeading
	{mso-style-priority:39;
	mso-style-qformat:yes;
	mso-style-parent:"Επικεφαλίδα 1";
	mso-style-next:Βασικό;
	margin-top:12.0pt;
	margin-right:0cm;
	margin-bottom:0cm;
	margin-left:0cm;
	margin-bottom:.0001pt;
	line-height:107%;
	mso-pagination:widow-orphan lines-together;
	page-break-after:avoid;
	font-size:16.0pt;
	font-family:"Calibri Light",sans-serif;
	mso-ascii-font-family:"Calibri Light";
	mso-ascii-theme-font:major-latin;
	mso-fareast-font-family:"DengXian Light";
	mso-fareast-theme-font:major-fareast;
	mso-hansi-font-family:"Calibri Light";
	mso-hansi-theme-font:major-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:major-bidi;
	color:#2E74B5;
	mso-themecolor:accent1;
	mso-themeshade:191;
	mso-fareast-language:EL;}
span.Char
	{mso-style-name:"Κεφαλίδα Char";
	mso-style-priority:99;
	mso-style-unhide:no;
	mso-style-locked:yes;
	mso-style-link:Κεφαλίδα;
	font-family:SimSun;
	mso-fareast-font-family:SimSun;}
span.Char0
	{mso-style-name:"Υποσέλιδο Char";
	mso-style-priority:99;
	mso-style-unhide:no;
	mso-style-locked:yes;
	mso-style-link:Υποσέλιδο;
	font-family:SimSun;
	mso-fareast-font-family:SimSun;}
span.Char1
	{mso-style-name:"Τίτλος Char";
	mso-style-priority:10;
	mso-style-unhide:no;
	mso-style-locked:yes;
	mso-style-link:Τίτλος;
	mso-ansi-font-size:28.0pt;
	mso-bidi-font-size:28.0pt;
	font-family:"Calibri Light",sans-serif;
	mso-ascii-font-family:"Calibri Light";
	mso-ascii-theme-font:major-latin;
	mso-fareast-font-family:"DengXian Light";
	mso-fareast-theme-font:major-fareast;
	mso-hansi-font-family:"Calibri Light";
	mso-hansi-theme-font:major-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:major-bidi;
	letter-spacing:-.5pt;
	mso-font-kerning:14.0pt;}
span.Char2
	{mso-style-name:"Κείμενο πλαισίου Char";
	mso-style-noshow:yes;
	mso-style-priority:99;
	mso-style-unhide:no;
	mso-style-locked:yes;
	mso-style-link:"Κείμενο πλαισίου";
	mso-ansi-font-size:8.0pt;
	mso-bidi-font-size:8.0pt;
	font-family:"Tahoma",sans-serif;
	mso-ascii-font-family:Tahoma;
	mso-fareast-font-family:SimSun;
	mso-hansi-font-family:Tahoma;
	mso-bidi-font-family:Tahoma;}
span.1Char
	{mso-style-name:"Επικεφαλίδα 1 Char";
	mso-style-priority:9;
	mso-style-unhide:no;
	mso-style-locked:yes;
	mso-style-link:"Επικεφαλίδα 1";
	mso-ansi-font-size:16.0pt;
	mso-bidi-font-size:16.0pt;
	font-family:"Calibri Light",sans-serif;
	mso-ascii-font-family:"Calibri Light";
	mso-ascii-theme-font:major-latin;
	mso-fareast-font-family:"DengXian Light";
	mso-fareast-theme-font:major-fareast;
	mso-hansi-font-family:"Calibri Light";
	mso-hansi-theme-font:major-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:major-bidi;
	color:#2E74B5;
	mso-themecolor:accent1;
	mso-themeshade:191;}
span.2Char
	{mso-style-name:"Επικεφαλίδα 2 Char";
	mso-style-priority:9;
	mso-style-unhide:no;
	mso-style-locked:yes;
	mso-style-link:"Επικεφαλίδα 2";
	mso-ansi-font-size:13.0pt;
	mso-bidi-font-size:13.0pt;
	font-family:"Calibri Light",sans-serif;
	mso-ascii-font-family:"Calibri Light";
	mso-ascii-theme-font:major-latin;
	mso-fareast-font-family:"DengXian Light";
	mso-fareast-theme-font:major-fareast;
	mso-hansi-font-family:"Calibri Light";
	mso-hansi-theme-font:major-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:major-bidi;
	color:#2E74B5;
	mso-themecolor:accent1;
	mso-themeshade:191;}
span.SpellE
	{mso-style-name:"";
	mso-spl-e:yes;}
.MsoChpDefault
	{mso-style-type:export-only;
	mso-default-props:yes;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-fareast-font-family:DengXian;
	mso-fareast-theme-font:minor-fareast;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-fareast-language:EN-US;}
.MsoPapDefault
	{mso-style-type:export-only;
	margin-bottom:8.0pt;
	line-height:107%;}
 /* Page Definitions */
 @page
	{mso-footnote-separator:url("Arduino_smart_garbadge_monitoring_system_2023_Readme1.files/header.html") fs;
	mso-footnote-continuation-separator:url("Arduino_smart_garbadge_monitoring_system_2023_Readme1.files/header.html") fcs;
	mso-endnote-separator:url("Arduino_smart_garbadge_monitoring_system_2023_Readme1.files/header.html") es;
	mso-endnote-continuation-separator:url("Arduino_smart_garbadge_monitoring_system_2023_Readme1.files/header.html") ecs;}
@page WordSection1
	{size:595.3pt 841.9pt;
	margin:72.0pt 49.55pt 72.0pt 90.0pt;
	mso-header-margin:35.4pt;
	mso-footer-margin:35.4pt;
	mso-paper-source:0;}
div.WordSection1
	{page:WordSection1;}
 /* List Definitions */
 @list l0
	{mso-list-id:544291187;
	mso-list-type:hybrid;
	mso-list-template-ids:1135613986 67633153 67633155 67633157 67633153 67633155 67633157 67633153 67633155 67633157;}
@list l0:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l0:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l0:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l0:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l0:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l0:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l0:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l0:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l0:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l1
	{mso-list-id:551502583;
	mso-list-type:hybrid;
	mso-list-template-ids:1623211668 67633167 67633177 67633179 67633167 67633177 67633179 67633167 67633177 67633179;}
@list l1:level1
	{mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l1:level2
	{mso-level-number-format:alpha-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l1:level3
	{mso-level-number-format:roman-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:right;
	text-indent:-9.0pt;}
@list l1:level4
	{mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l1:level5
	{mso-level-number-format:alpha-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l1:level6
	{mso-level-number-format:roman-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:right;
	text-indent:-9.0pt;}
@list l1:level7
	{mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l1:level8
	{mso-level-number-format:alpha-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;}
@list l1:level9
	{mso-level-number-format:roman-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:right;
	text-indent:-9.0pt;}
@list l2
	{mso-list-id:1038580933;
	mso-list-type:hybrid;
	mso-list-template-ids:-986295764 67633153 67633155 67633157 67633153 67633155 67633157 67633153 67633155 67633157;}
@list l2:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l2:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l2:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l2:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l2:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l2:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l2:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l2:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l2:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l3
	{mso-list-id:1096441040;
	mso-list-type:hybrid;
	mso-list-template-ids:-1321033700 67633153 67633155 67633157 67633153 67633155 67633157 67633153 67633155 67633157;}
@list l3:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l3:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l3:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l3:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l3:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l3:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l3:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l3:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l3:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l4
	{mso-list-id:1342466534;
	mso-list-type:hybrid;
	mso-list-template-ids:118514930 1672524066 67633177 67633179 67633167 67633177 67633179 67633167 67633177 67633179;}
@list l4:level1
	{mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:54.0pt;
	text-indent:-18.0pt;}
@list l4:level2
	{mso-level-number-format:alpha-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:90.0pt;
	text-indent:-18.0pt;}
@list l4:level3
	{mso-level-number-format:roman-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:right;
	margin-left:126.0pt;
	text-indent:-9.0pt;}
@list l4:level4
	{mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:162.0pt;
	text-indent:-18.0pt;}
@list l4:level5
	{mso-level-number-format:alpha-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:198.0pt;
	text-indent:-18.0pt;}
@list l4:level6
	{mso-level-number-format:roman-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:right;
	margin-left:234.0pt;
	text-indent:-9.0pt;}
@list l4:level7
	{mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:270.0pt;
	text-indent:-18.0pt;}
@list l4:level8
	{mso-level-number-format:alpha-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	margin-left:306.0pt;
	text-indent:-18.0pt;}
@list l4:level9
	{mso-level-number-format:roman-lower;
	mso-level-tab-stop:none;
	mso-level-number-position:right;
	margin-left:342.0pt;
	text-indent:-9.0pt;}
@list l5
	{mso-list-id:2071998813;
	mso-list-type:hybrid;
	mso-list-template-ids:-350089418 67633153 67633155 67633157 67633153 67633155 67633157 67633153 67633155 67633157;}
@list l5:level1
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l5:level2
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l5:level3
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l5:level4
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l5:level5
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l5:level6
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
@list l5:level7
	{mso-level-number-format:bullet;
	mso-level-text:\F0B7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Symbol;}
@list l5:level8
	{mso-level-number-format:bullet;
	mso-level-text:o;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:"Courier New";}
@list l5:level9
	{mso-level-number-format:bullet;
	mso-level-text:\F0A7;
	mso-level-tab-stop:none;
	mso-level-number-position:left;
	text-indent:-18.0pt;
	font-family:Wingdings;}
ol
	{margin-bottom:0cm;}
ul
	{margin-bottom:0cm;}
-->
</style>
<!--[if gte mso 10]>
<style>
 /* Style Definitions */
 table.MsoNormalTable
	{mso-style-name:"Κανονικός πίνακας";
	mso-tstyle-rowband-size:0;
	mso-tstyle-colband-size:0;
	mso-style-noshow:yes;Per
	mso-style-priority:99;
	mso-style-parent:"";
	mso-padding-alt:0cm 5.4pt 0cm 5.4pt;
	mso-para-margin-top:0cm;
	mso-para-margin-right:0cm;
	mso-para-margin-bottom:8.0pt;
	mso-para-margin-left:0cm;
	line-height:107%;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-fareast-language:EN-US;}
table.MsoTableGrid
	{mso-style-name:"Πλέγμα πίνακα";
	mso-tstyle-rowband-size:0;
	mso-tstyle-colband-size:0;
	mso-style-priority:39;
	mso-style-unhide:no;
	border:solid windowtext 1.0pt;
	mso-border-alt:solid windowtext .5pt;
	mso-padding-alt:0cm 5.4pt 0cm 5.4pt;
	mso-border-insideh:.5pt solid windowtext;
	mso-border-insidev:.5pt solid windowtext;
	mso-para-margin:0cm;
	mso-para-margin-bottom:.0001pt;
	mso-pagination:widow-orphan;
	font-size:11.0pt;
	font-family:"Calibri",sans-serif;
	mso-ascii-font-family:Calibri;
	mso-ascii-theme-font:minor-latin;
	mso-hansi-font-family:Calibri;
	mso-hansi-theme-font:minor-latin;
	mso-bidi-font-family:"Times New Roman";
	mso-bidi-theme-font:minor-bidi;
	mso-fareast-language:EN-US;}
</style>
<![endif]--><!--[if gte mso 9]><xml>
 <o:shapedefaults v:ext="edit" spidmax="2049"/>
</xml><![endif]--><!--[if gte mso 9]><xml>
 <o:shapelayout v:ext="edit">
  <o:idmap v:ext="edit" data="1"/>
 </o:shapelayout></xml><![endif]-->
</head>

<body lang=EL link="#0563C1" vlink="#954F72" style='tab-interval:36.0pt'>

<div class=WordSection1>

 

 
 <p class=MsoTocHeading>Περιεχόμενα<span style='font-size:11.0pt;line-height:
 107%;mso-ascii-font-family:Calibri;mso-ascii-theme-font:minor-latin;
 mso-fareast-font-family:SimSun;mso-hansi-font-family:Calibri;mso-hansi-theme-font:
 minor-latin;mso-bidi-font-family:"Times New Roman";mso-bidi-theme-font:minor-bidi;
 color:windowtext;mso-fareast-language:EN-US'><w:sdtPr></w:sdtPr></span></p>
 <p class=MsoToc1 style='tab-stops:right dotted 455.25pt'><!--[if supportFields]><span
 style='mso-element:field-begin'></span><span
 style='mso-spacerun:yes'> </span>TOC \o &quot;1-3&quot; \n \h \z \u <span
 style='mso-element:field-separator'></span><![endif]--><a href="#_Toc137899619"><span
 style='mso-fareast-language:EL;mso-no-proof:yes'>Εισαγωγή</span></a><span
 style='mso-fareast-font-family:DengXian;mso-fareast-theme-font:minor-fareast;
 mso-fareast-language:EL;mso-no-proof:yes'><o:p></o:p></span></p>
 <p class=MsoToc1 style='tab-stops:right dotted 455.25pt'><a
 href="#_Toc137899620"><span style='mso-fareast-language:EL;mso-no-proof:yes'>Σενάριο
 Χρήσης</span></a><span style='mso-fareast-font-family:DengXian;mso-fareast-theme-font:
 minor-fareast;mso-fareast-language:EL;mso-no-proof:yes'><o:p></o:p></span></p>
 <p class=MsoToc1 style='tab-stops:right dotted 455.25pt'><a
 href="#_Toc137899621"><span style='mso-fareast-language:ZH-CN;mso-no-proof:
 yes'>Στόχος Εφαρμογής</span></a><span style='mso-fareast-font-family:DengXian;
 mso-fareast-theme-font:minor-fareast;mso-fareast-language:EL;mso-no-proof:
 yes'><o:p></o:p></span></p>
 <p class=MsoToc1 style='tab-stops:right dotted 455.25pt'><a
 href="#_Toc137899622"><span style='mso-fareast-language:ZH-CN;mso-no-proof:
 yes'>Προτεινόμενη Λύση</span></a><span style='mso-fareast-font-family:DengXian;
 mso-fareast-theme-font:minor-fareast;mso-fareast-language:EL;mso-no-proof:
 yes'><o:p></o:p></span></p>
 <p class=MsoToc1 style='tab-stops:right dotted 455.25pt'><a
 href="#_Toc137899623"><span style='mso-fareast-language:ZH-CN;mso-no-proof:
 yes'>Σενάριο&nbsp;Δραστηριότητας</span></a><span style='mso-fareast-font-family:
 DengXian;mso-fareast-theme-font:minor-fareast;mso-fareast-language:EL;
 mso-no-proof:yes'><o:p></o:p></span></p>
 <p class=MsoToc1 style='tab-stops:right dotted 455.25pt'><a
 href="#_Toc137899624"><span style='mso-fareast-language:ZH-CN;mso-no-proof:
 yes'>Φάση Προετοιμασίας</span></a><span style='mso-fareast-font-family:DengXian;
 mso-fareast-theme-font:minor-fareast;mso-fareast-language:EL;mso-no-proof:
 yes'><o:p></o:p></span></p>
 <p class=MsoToc1 style='tab-stops:right dotted 455.25pt'><a
 href="#_Toc137899625"><span style='mso-no-proof:yes'>Φάση σχεδιασμού</span></a><span
 style='mso-fareast-font-family:DengXian;mso-fareast-theme-font:minor-fareast;
 mso-fareast-language:EL;mso-no-proof:yes'><o:p></o:p></span></p>
 <p class=MsoToc1 style='tab-stops:right dotted 455.25pt'><a
 href="#_Toc137899626"><span style='mso-no-proof:yes'>Δυσκολίες που
 αντιμετωπίσαμε</span></a><span style='mso-fareast-font-family:DengXian;
 mso-fareast-theme-font:minor-fareast;mso-fareast-language:EL;mso-no-proof:
 yes'><o:p></o:p></span></p>
 <p class=MsoToc1 style='tab-stops:right dotted 455.25pt'><a
 href="#_Toc137899627"><span style='mso-no-proof:yes'>Σε τι μας βοηθάει</span></a><span
 style='mso-fareast-font-family:DengXian;mso-fareast-theme-font:minor-fareast;
 mso-fareast-language:EL;mso-no-proof:yes'><o:p></o:p></span></p>
 <p class=MsoToc1 style='tab-stops:right dotted 455.25pt'><a
 href="#_Toc137899628"><span style='mso-no-proof:yes'>Κώδικας </span><span
 lang=EN-US style='mso-ansi-language:EN-US;mso-no-proof:yes'>Arduino</span><span
 lang=EN-US style='mso-no-proof:yes'> </span><span lang=EN-US style='mso-ansi-language:
 EN-US;mso-no-proof:yes'>IDE</span></a><span style='mso-fareast-font-family:
 DengXian;mso-fareast-theme-font:minor-fareast;mso-fareast-language:EL;
 mso-no-proof:yes'><o:p></o:p></span></p>
 <p class=MsoToc1 style='tab-stops:right dotted 455.25pt'><a
 href="#_Toc137899629"><span style='mso-no-proof:yes'>Μελλοντικές εξελίξεις</span></a><span
 style='mso-fareast-font-family:DengXian;mso-fareast-theme-font:minor-fareast;
 mso-fareast-language:EL;mso-no-proof:yes'><o:p></o:p></span></p>
 <p class=MsoToc1 style='tab-stops:right dotted 455.25pt'><a
 href="#_Toc137899630"><span style='mso-no-proof:yes'>Πλατφόρμες που
 χρησιμοποιήθηκαν</span></a><span style='mso-fareast-font-family:DengXian;
 mso-fareast-theme-font:minor-fareast;mso-fareast-language:EL;mso-no-proof:
 yes'><o:p></o:p></span></p>
 <p class=MsoToc1 style='tab-stops:right dotted 455.25pt'><a
 href="#_Toc137899631"><span style='mso-no-proof:yes'>Υλοποίηση</span></a><span
 style='mso-fareast-font-family:DengXian;mso-fareast-theme-font:minor-fareast;
 mso-fareast-language:EL;mso-no-proof:yes'><o:p></o:p></span></p>
 <p class=MsoToc1 style='tab-stops:right dotted 455.25pt'><a
 href="#_Toc137899632"><span style='mso-no-proof:yes'>Φάση Δοκιμών</span></a><span
 style='mso-fareast-font-family:DengXian;mso-fareast-theme-font:minor-fareast;
 mso-fareast-language:EL;mso-no-proof:yes'><o:p></o:p></span></p>
 <p class=MsoToc1 style='tab-stops:right dotted 455.25pt'><a
 href="#_Toc137899633"><span style='mso-no-proof:yes'>Συμπεράσματα</span></a><span
 style='mso-fareast-font-family:DengXian;mso-fareast-theme-font:minor-fareast;
 mso-fareast-language:EL;mso-no-proof:yes'><o:p></o:p></span></p>
 <p class=MsoNormal><!--[if supportFields]><span style='mso-element:field-end'></span><![endif]--><o:p>&nbsp;</o:p></p>
</w:Sdt>

<p class=MsoNormal style='mso-margin-top-alt:auto;margin-bottom:12.0pt;
text-align:justify;text-justify:inter-ideograph;line-height:normal;background:
white'><b><span lang=EN-US style='font-size:14.0pt;font-family:"Helvetica",sans-serif;
mso-fareast-font-family:"Times New Roman";color:#24292F;mso-ansi-language:EN-US;
mso-fareast-language:EL'><o:p>&nbsp;</o:p></span></b></p>

<h1><a name="_Toc137899618"><span style='mso-fareast-language:EL'>Περιεχόμενα</span></a><span
style='mso-fareast-language:EL'><o:p></o:p></span></h1>

<p class=MsoListParagraphCxSpFirst style='mso-margin-top-alt:auto;margin-bottom:
12.0pt;mso-add-space:auto;text-align:justify;text-justify:inter-ideograph;
text-indent:-18.0pt;line-height:normal;mso-list:l0 level1 lfo2;background:white'><![if !supportLists]><span
style='font-size:14.0pt;font-family:Symbol;mso-fareast-font-family:Symbol;
mso-bidi-font-family:Symbol;color:#24292F;mso-fareast-language:EL;mso-bidi-font-weight:
bold'><span style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span style='font-size:14.0pt;font-family:
"Comic Sans MS";mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:
Helvetica;color:#24292F;mso-fareast-language:EL'>Εισαγωγή<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='mso-margin-top-alt:auto;margin-bottom:
12.0pt;mso-add-space:auto;text-align:justify;text-justify:inter-ideograph;
text-indent:-18.0pt;line-height:normal;mso-list:l0 level1 lfo2;background:white'><![if !supportLists]><span
style='font-size:14.0pt;font-family:Symbol;mso-fareast-font-family:Symbol;
mso-bidi-font-family:Symbol;color:#24292F;mso-fareast-language:EL;mso-bidi-font-weight:
bold'><span style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span style='font-size:14.0pt;font-family:
"Comic Sans MS";mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:
Helvetica;color:#24292F;mso-fareast-language:EL'>Σενάριο Χρήσης<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='mso-margin-top-alt:auto;margin-bottom:
12.0pt;mso-add-space:auto;text-align:justify;text-justify:inter-ideograph;
text-indent:-18.0pt;line-height:normal;mso-list:l0 level1 lfo2;background:white'><![if !supportLists]><span
style='font-size:14.0pt;font-family:Symbol;mso-fareast-font-family:Symbol;
mso-bidi-font-family:Symbol;color:#24292F;mso-fareast-language:EL;mso-bidi-font-weight:
bold'><span style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span style='font-size:14.0pt;font-family:
"Comic Sans MS";mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:
Helvetica;color:#24292F;mso-fareast-language:EL'>Στόχος Εφαρμογής<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='mso-margin-top-alt:auto;margin-bottom:
12.0pt;mso-add-space:auto;text-align:justify;text-justify:inter-ideograph;
text-indent:-18.0pt;line-height:normal;mso-list:l0 level1 lfo2;background:white'><![if !supportLists]><span
style='font-size:14.0pt;font-family:Symbol;mso-fareast-font-family:Symbol;
mso-bidi-font-family:Symbol;color:#24292F;mso-fareast-language:EL;mso-bidi-font-weight:
bold'><span style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span style='font-size:14.0pt;font-family:
"Comic Sans MS";mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:
Helvetica;color:#24292F;mso-fareast-language:EL'>Προτεινόμενη Λύση<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='mso-margin-top-alt:auto;margin-bottom:
12.0pt;mso-add-space:auto;text-align:justify;text-justify:inter-ideograph;
text-indent:-18.0pt;line-height:normal;mso-list:l0 level1 lfo2;background:white'><![if !supportLists]><span
style='font-size:14.0pt;font-family:Symbol;mso-fareast-font-family:Symbol;
mso-bidi-font-family:Symbol;color:#24292F;mso-fareast-language:EL;mso-bidi-font-weight:
bold'><span style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span style='font-size:14.0pt;font-family:
"Comic Sans MS";mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:
Helvetica;color:#24292F;mso-fareast-language:EL'>Σενάριο Δραστηριότητας<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='mso-margin-top-alt:auto;margin-bottom:
12.0pt;mso-add-space:auto;text-align:justify;text-justify:inter-ideograph;
text-indent:-18.0pt;line-height:normal;mso-list:l0 level1 lfo2;background:white'><![if !supportLists]><span
style='font-size:14.0pt;font-family:Symbol;mso-fareast-font-family:Symbol;
mso-bidi-font-family:Symbol;color:#24292F;mso-fareast-language:EL;mso-bidi-font-weight:
bold'><span style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span style='font-size:14.0pt;font-family:
"Comic Sans MS";mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:
"Segoe UI";color:#1F2328;mso-fareast-language:ZH-CN'>Φάση Προετοιμασίας</span></b><b><span
style='font-size:14.0pt;font-family:"Comic Sans MS";mso-fareast-font-family:
"Times New Roman";mso-bidi-font-family:Helvetica;color:#24292F;mso-fareast-language:
EL'><o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='mso-margin-top-alt:auto;margin-bottom:
12.0pt;mso-add-space:auto;text-align:justify;text-justify:inter-ideograph;
text-indent:-18.0pt;line-height:normal;mso-list:l0 level1 lfo2;background:white'><![if !supportLists]><span
style='font-size:14.0pt;font-family:Symbol;mso-fareast-font-family:Symbol;
mso-bidi-font-family:Symbol;color:#24292F;mso-fareast-language:EL;mso-bidi-font-weight:
bold'><span style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span style='font-size:14.0pt;font-family:
"Comic Sans MS";mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:
"Segoe UI";color:#1F2328;mso-fareast-language:ZH-CN'>Φάση Σχεδιασμού</span></b><b><span
style='font-size:14.0pt;font-family:"Comic Sans MS";mso-fareast-font-family:
"Times New Roman";mso-bidi-font-family:Helvetica;color:#24292F;mso-fareast-language:
EL'><o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='mso-margin-top-alt:auto;margin-bottom:
12.0pt;mso-add-space:auto;text-align:justify;text-justify:inter-ideograph;
text-indent:-18.0pt;line-height:normal;mso-list:l0 level1 lfo2;background:white'><![if !supportLists]><span
style='font-size:14.0pt;font-family:Symbol;mso-fareast-font-family:Symbol;
mso-bidi-font-family:Symbol;color:#24292F;mso-fareast-language:EL;mso-bidi-font-weight:
bold'><span style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span style='font-size:14.0pt;font-family:
"Comic Sans MS";mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:
"Segoe UI";color:#1F2328;mso-fareast-language:ZH-CN'>Σε τι μας βοηθάει</span></b><b><span
style='font-size:14.0pt;font-family:"Comic Sans MS";mso-fareast-font-family:
"Times New Roman";mso-bidi-font-family:Helvetica;color:#24292F;mso-fareast-language:
EL'><o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='mso-margin-top-alt:auto;margin-bottom:
12.0pt;mso-add-space:auto;text-align:justify;text-justify:inter-ideograph;
text-indent:-18.0pt;line-height:normal;mso-list:l0 level1 lfo2;background:white'><![if !supportLists]><span
style='font-size:14.0pt;font-family:Symbol;mso-fareast-font-family:Symbol;
mso-bidi-font-family:Symbol;color:#24292F;mso-fareast-language:EL;mso-bidi-font-weight:
bold'><span style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span style='font-size:14.0pt;font-family:
"Comic Sans MS";mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:
"Segoe UI";color:#1F2328;mso-fareast-language:ZH-CN'>Δυσκολίες που
αντιμετωπίσαμε</span></b><b><span style='font-size:14.0pt;font-family:"Comic Sans MS";
mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:Helvetica;
color:#24292F;mso-fareast-language:EL'><o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='mso-margin-top-alt:auto;margin-bottom:
12.0pt;mso-add-space:auto;text-align:justify;text-justify:inter-ideograph;
text-indent:-18.0pt;line-height:normal;mso-list:l0 level1 lfo2;background:white'><![if !supportLists]><span
style='font-size:14.0pt;font-family:Symbol;mso-fareast-font-family:Symbol;
mso-bidi-font-family:Symbol;color:#24292F;mso-fareast-language:EL;mso-bidi-font-weight:
bold'><span style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span style='font-size:14.0pt;font-family:
"Comic Sans MS";mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:
"Segoe UI";color:#1F2328;mso-fareast-language:ZH-CN'>Μελλοντικές εξελίξεις</span></b><b><span
style='font-size:14.0pt;font-family:"Comic Sans MS";mso-fareast-font-family:
"Times New Roman";mso-bidi-font-family:Helvetica;color:#24292F;mso-fareast-language:
EL'><o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='mso-margin-top-alt:auto;margin-bottom:
12.0pt;mso-add-space:auto;text-align:justify;text-justify:inter-ideograph;
text-indent:-18.0pt;line-height:normal;mso-list:l0 level1 lfo2;background:white'><![if !supportLists]><span
style='font-size:14.0pt;font-family:Symbol;mso-fareast-font-family:Symbol;
mso-bidi-font-family:Symbol;color:#24292F;mso-fareast-language:EL;mso-bidi-font-weight:
bold'><span style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span style='font-size:14.0pt;font-family:
"Comic Sans MS";mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:
"Segoe UI";color:#1F2328;mso-fareast-language:ZH-CN'>Κώδικας </span></b><b><span
lang=EN-US style='font-size:14.0pt;font-family:"Comic Sans MS";mso-fareast-font-family:
"Times New Roman";mso-bidi-font-family:"Segoe UI";color:#1F2328;mso-ansi-language:
EN-US;mso-fareast-language:ZH-CN'>Arduino IDE</span></b><b><span
style='font-size:14.0pt;font-family:"Comic Sans MS";mso-fareast-font-family:
"Times New Roman";mso-bidi-font-family:Helvetica;color:#24292F;mso-fareast-language:
EL'><o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='mso-margin-top-alt:auto;margin-bottom:
12.0pt;mso-add-space:auto;text-align:justify;text-justify:inter-ideograph;
text-indent:-18.0pt;line-height:normal;mso-list:l0 level1 lfo2;background:white'><![if !supportLists]><span
style='font-size:14.0pt;font-family:Symbol;mso-fareast-font-family:Symbol;
mso-bidi-font-family:Symbol;color:#24292F;mso-fareast-language:EL;mso-bidi-font-weight:
bold'><span style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span style='font-size:14.0pt;font-family:
"Comic Sans MS";mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:
"Segoe UI";color:#1F2328;mso-fareast-language:ZH-CN'>Πλατφόρμες που
χρησιμοποιήθηκαν</span></b><b><span style='font-size:14.0pt;font-family:"Comic Sans MS";
mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:Helvetica;
color:#24292F;mso-fareast-language:EL'><o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='mso-margin-top-alt:auto;margin-bottom:
12.0pt;mso-add-space:auto;text-align:justify;text-justify:inter-ideograph;
text-indent:-18.0pt;line-height:normal;mso-list:l0 level1 lfo2;background:white'><![if !supportLists]><span
style='font-size:14.0pt;font-family:Symbol;mso-fareast-font-family:Symbol;
mso-bidi-font-family:Symbol;color:#24292F;mso-fareast-language:EL;mso-bidi-font-weight:
bold'><span style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span style='font-size:14.0pt;font-family:
"Comic Sans MS";mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:
Helvetica;color:#24292F;mso-fareast-language:EL'>Υλοποίηση<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpMiddle style='mso-margin-top-alt:auto;margin-bottom:
12.0pt;mso-add-space:auto;text-align:justify;text-justify:inter-ideograph;
text-indent:-18.0pt;line-height:normal;mso-list:l0 level1 lfo2;background:white'><![if !supportLists]><span
style='font-size:14.0pt;font-family:Symbol;mso-fareast-font-family:Symbol;
mso-bidi-font-family:Symbol;color:#24292F;mso-fareast-language:EL;mso-bidi-font-weight:
bold'><span style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span style='font-size:14.0pt;font-family:
"Comic Sans MS";mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:
Helvetica;color:#24292F;mso-fareast-language:EL'>Φάση Δοκιμών<o:p></o:p></span></b></p>

<p class=MsoListParagraphCxSpLast style='mso-margin-top-alt:auto;margin-bottom:
12.0pt;mso-add-space:auto;text-align:justify;text-justify:inter-ideograph;
text-indent:-18.0pt;line-height:normal;mso-list:l0 level1 lfo2;background:white'><![if !supportLists]><span
style='font-size:14.0pt;font-family:Symbol;mso-fareast-font-family:Symbol;
mso-bidi-font-family:Symbol;color:#24292F;mso-fareast-language:EL;mso-bidi-font-weight:
bold'><span style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><b><span style='font-size:14.0pt;font-family:
"Comic Sans MS";mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:
Helvetica;color:#24292F;mso-fareast-language:EL'>Συμπεράσματα<o:p></o:p></span></b></p>

<h1><a name="_Toc137899619"><span style='mso-fareast-language:EL'>Εισαγωγή</span></a><span
style='mso-fareast-language:EL'><o:p></o:p></span></h1>

<p class=MsoNormal style='mso-margin-top-alt:auto;margin-bottom:12.0pt;
text-align:justify;text-justify:inter-ideograph;text-indent:36.0pt;line-height:
normal;background:white'><span style='font-size:12.0pt;font-family:"Comic Sans MS";
mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:Helvetica;
color:#24292F;mso-fareast-language:EL;mso-bidi-font-weight:bold'>Η διαδικασία
της καθημερινής συλλογής των αστικών οικιακών απορριμμάτων στις μεγάλες κυρίως
πόλεις, μπορεί να «κρύβει» μια σπατάλη ενέργειας που στην σημερινή εποχή της
κλιματικής αλλαγής θα ήταν προτιμότερο να μπορούσαμε να την αποφύγουμε. Πιο
συγκεκριμένα οι υπάλληλοι που χειρίζονται τα μηχανήματα αποκομιδής σκουπιδιών
από τους γνωστούς μας κάδους, έχουν ένα καθημερινό δρομολόγιο μέσα στους
δρόμους μιας μεγαλούπολης, με σκοπό να αδειάσουν τους </span><span
style='font-size:12.0pt;font-family:"Comic Sans MS";mso-fareast-font-family:
"Times New Roman";mso-bidi-font-family:Helvetica;color:#7030A0;mso-fareast-language:
EL;mso-bidi-font-weight:bold'>«πιθανώς»</span><span style='font-size:12.0pt;
font-family:"Comic Sans MS";mso-fareast-font-family:"Times New Roman";
mso-bidi-font-family:Helvetica;color:#24292F;mso-fareast-language:EL;
mso-bidi-font-weight:bold'> γεμάτους κάδους από τα σκουπίδια. Ο σχεδιασμός της
αποκομιδής, υποθέτει βάσει της πρότερης εμπειρίας τους, ότι είναι τόσο γεμάτοι
ώστε να μην μπορεί να παραληφθούν για έστω και μία ημέρα , από τα μηχανήματα
αποκομιδής. κατά την κυκλοφορία τους καθημερινά μέσα στην πόλη.<o:p></o:p></span></p>

<p class=MsoNormal style='mso-margin-top-alt:auto;margin-bottom:12.0pt;
text-align:justify;text-justify:inter-ideograph;text-indent:36.0pt;line-height:
normal;background:white'><span style='font-size:12.0pt;font-family:"Comic Sans MS";
mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:Helvetica;
color:#24292F;mso-fareast-language:EL;mso-bidi-font-weight:bold'>Είναι όμως
ακριβώς έτσι; <span style='mso-spacerun:yes'> </span>Αν για παράδειγμα κάποιοι
κάδοι , από τους οποίους περνάνε τα μηχανήματα είναι μισοάδειοι και θα
μπορούσαν να παραμείνουν μέχρι και την επόμενη ημέρα, για να αδειάσουν , τότε
μήπως το μηχάνημα αποκομιδής σπατάλησε ενέργεια σε καύσιμα, χρόνο, ανθρωποώρες
εργασίας από τους υπαλλήλους και τελικώς επιβάρυνε και την κυκλοφορία της
πόλης; Επιπλέον αν κάποιοι κάδοι λόγω κάπου ειδικού και έκτακτου γεγονότος στην
περιοχή, γέμισαν νωρίτερα από το «προβλεπόμενο» χρόνο, τότε αυτή η «αλάνθαστη»
καθημερινή εμπειρία χρήσης δεν είναι τελικά η ενδεδειγμένη διαδικασία αποκομιδής
απορριμμάτων μέσα σε μία πόλη;<o:p></o:p></span></p>

<h1><a name="_Toc137899620"><span style='mso-fareast-language:EL'>Σενάριο Χρήσης</span></a><span
style='mso-fareast-language:EL'><o:p></o:p></span></h1>

<p class=MsoNormalCxSpFirst style='margin-bottom:0cm;margin-bottom:.0001pt;
mso-add-space:auto;text-align:justify;text-justify:inter-ideograph;text-indent:
36.0pt;line-height:normal;background:white'><span style='font-size:12.0pt;
font-family:"Comic Sans MS";mso-fareast-font-family:"Times New Roman";
mso-bidi-font-family:Helvetica;color:#1D2228;mso-fareast-language:EL'>Ένας
αισθητήρας υπερήχων (<i style='mso-bidi-font-style:normal'>ένας αισθητήρας
απόστασης)</i> θα τοποθετηθεί στην εσωτερική πλευρά του καπακιού, αυτή που
βλέπει τα στερεά απόβλητα. Καθώς τα σκουπίδια αυξάνονται, η απόσταση μεταξύ του
υπερήχου και των σκουπιδιών μειώνεται. Αυτά τα ζωντανά δεδομένα θα σταλούν στον
μικροελεγκτή μας.<span style='mso-tab-count:1'>   </span>Στη συνέχεια, ο
μικροελεγκτής μας επεξεργάζεται τα δεδομένα και μέσω της βοήθειας <span
class=SpellE>WiFi</span> τα στέλνει σε μια εφαρμογή.<o:p></o:p></span></p>

<p class=MsoNormalCxSpMiddle style='margin-bottom:0cm;margin-bottom:.0001pt;
mso-add-space:auto;text-align:justify;text-justify:inter-ideograph;text-indent:
36.0pt;line-height:normal;background:white'><span style='font-size:12.0pt;
font-family:"Comic Sans MS";mso-fareast-font-family:"Times New Roman";
mso-bidi-font-family:Helvetica;color:#1D2228;mso-fareast-language:EL'>Αυτό που
κάνει η εφαρμογή αντιπροσωπεύει οπτικά την ποσότητα των σκουπιδιών στον κάδο με
μια μικρή κινούμενη εικόνα.<o:p></o:p></span></p>

<p class=MsoNormalCxSpMiddle style='margin-bottom:0cm;margin-bottom:.0001pt;
mso-add-space:auto;text-align:justify;text-justify:inter-ideograph;text-indent:
36.0pt;line-height:normal;background:white'><span style='font-size:12.0pt;
font-family:"Comic Sans MS";mso-fareast-font-family:"Times New Roman";
mso-bidi-font-family:Helvetica;color:#1D2228;mso-fareast-language:EL'>Αυτή η
διαδικασία θα υποδείξει όλους τους κάδους που απαιτούν προσοχή, οδηγώντας τον
χρήστη να ακολουθήσει την πιο αποτελεσματική διαδρομή.</span><span
style='font-family:"Comic Sans MS";mso-fareast-language:ZH-CN;mso-no-proof:
yes'> </span><span style='font-size:12.0pt;font-family:"Comic Sans MS";
mso-fareast-font-family:"Times New Roman";mso-bidi-font-family:Helvetica;
color:#1D2228;mso-fareast-language:EL'><o:p></o:p></span></p>

<p class=MsoNormal><span style='font-family:"Comic Sans MS"'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal align=center style='text-align:center'><span
style='font-family:"Comic Sans MS";mso-fareast-language:ZH-CN;mso-no-proof:
yes'><!--[if gte vml 1]><v:shapetype id="_x0000_t75" coordsize="21600,21600"
 o:spt="75" o:preferrelative="t" path="m@4@5l@4@11@9@11@9@5xe" filled="f"
 stroked="f">
 <v:stroke joinstyle="miter"/>
 <v:formulas>
  <v:f eqn="if lineDrawn pixelLineWidth 0"/>
  <v:f eqn="sum @0 1 0"/>
  <v:f eqn="sum 0 0 @1"/>
  <v:f eqn="prod @2 1 2"/>
  <v:f eqn="prod @3 21600 pixelWidth"/>
  <v:f eqn="prod @3 21600 pixelHeight"/>
  <v:f eqn="sum @0 0 1"/>
  <v:f eqn="prod @6 1 2"/>
  <v:f eqn="prod @7 21600 pixelWidth"/>
  <v:f eqn="sum @8 21600 0"/>
  <v:f eqn="prod @7 21600 pixelHeight"/>
  <v:f eqn="sum @10 21600 0"/>
 </v:formulas>
 <v:path o:extrusionok="f" gradientshapeok="t" o:connecttype="rect"/>
 <o:lock v:ext="edit" aspectratio="t"/>
</v:shapetype><v:shape id="Εικόνα_x0020_1" o:spid="_x0000_i1026" type="#_x0000_t75"
 style='width:445.8pt;height:188.4pt;visibility:visible;mso-wrap-style:square'>
 <v:imagedata src="images/1.png"
  o:title=""/>
</v:shape><![endif]--><![if !vml]><img border=0 width=594 height=251
src="Arduino_smart_garbadge_monitoring_system_2023_Readme1.files/image002.png"
v:shapes="Εικόνα_x0020_1"><![endif]></span><span lang=EN-US style='font-family:
"Comic Sans MS";mso-ansi-language:EN-US'><o:p></o:p></span></p>

<p class=MsoNormal align=right style='text-align:right'><span lang=EN-US
style='font-family:"Comic Sans MS";mso-ansi-language:EN-US'><o:p>&nbsp;</o:p></span></p>

<p class=MsoNormal align=center style='text-align:center'><span
style='font-family:"Comic Sans MS";mso-fareast-language:ZH-CN;mso-no-proof:
yes'><!--[if gte vml 1]><v:shape id="Εικόνα_x0020_2" o:spid="_x0000_i1025"
 type="#_x0000_t75" style='width:473.4pt;height:179.4pt;visibility:visible;
 mso-wrap-style:square'>
 <v:imagedata src="Arduino_smart_garbadge_monitoring_system_2023_Readme1.files/image003.png"
  o:title=""/>
</v:shape><![endif]--><![if !vml]><img border=0 width=631 height=239
src="Arduino_smart_garbadge_monitoring_system_2023_Readme1.files/image004.jpg"
v:shapes="Εικόνα_x0020_2"><![endif]></span><span style='font-family:"Comic Sans MS"'><o:p></o:p></span></p>

<p class=MsoNormal style='margin-right:11.3pt;text-align:justify;text-justify:
inter-ideograph;text-indent:36.0pt'><span style='font-size:12.0pt;line-height:
107%;font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;mso-fareast-language:
ZH-CN'>Σε κάθε κάδο υπάρχει ένας <span style='color:red'>αισθητήρας </span></span><span
style='font-size:12.0pt;line-height:107%;font-family:"Comic Sans MS";
mso-bidi-font-family:Helvetica;color:black;mso-themecolor:text1'>, </span><span
style='font-size:12.0pt;line-height:107%;font-family:"Comic Sans MS";
mso-bidi-font-family:Helvetica;color:black;mso-themecolor:text1;mso-fareast-language:
ZH-CN'>ο οποίος βλέπει πόσο γεμάτος είναι ο κάδος. Όταν ο κάδος είναι γεμάτος
τότε το </span><span class=SpellE><span style='font-size:12.0pt;line-height:
107%;font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;color:#002060;
mso-fareast-language:ZH-CN'>τσιπάκι</span></span><span style='font-size:12.0pt;
line-height:107%;font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;
color:#002060;mso-fareast-language:ZH-CN'> </span><span style='font-size:12.0pt;
line-height:107%;font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;
color:black;mso-themecolor:text1;mso-fareast-language:ZH-CN'>στέλνει μήνυμα
μέσω </span><span lang=EN-GB style='font-size:12.0pt;line-height:107%;
font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;
mso-themecolor:text1;mso-ansi-language:EN-GB;mso-fareast-language:ZH-CN'>Wi</span><span
style='font-size:12.0pt;line-height:107%;font-family:"Comic Sans MS";
mso-bidi-font-family:Helvetica;color:black;mso-themecolor:text1;mso-fareast-language:
ZH-CN'>-</span><span lang=EN-GB style='font-size:12.0pt;line-height:107%;
font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;
mso-themecolor:text1;mso-ansi-language:EN-GB;mso-fareast-language:ZH-CN'>Fi</span><span
style='font-size:12.0pt;line-height:107%;font-family:"Comic Sans MS";
mso-bidi-font-family:Helvetica;color:black;mso-themecolor:text1;mso-fareast-language:
ZH-CN'> στην εφαρμογή.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-right:11.3pt;text-align:justify;text-justify:
inter-ideograph;text-indent:36.0pt'><span style='font-size:12.0pt;line-height:
107%;font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;
mso-themecolor:text1;mso-fareast-language:ZH-CN'>Υλικά<o:p></o:p></span></p>

<table class=MsoTableGrid border=1 cellspacing=0 cellpadding=0
 style='border-collapse:collapse;border:none;mso-border-alt:solid windowtext .5pt;
 mso-yfti-tbllook:1184;mso-padding-alt:0cm 5.4pt 0cm 5.4pt'>
 <tr style='mso-yfti-irow:0;mso-yfti-firstrow:yes;height:16.5pt'>
  <td width=193 valign=top style='width:144.75pt;border:solid windowtext 1.0pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span style='font-size:12.0pt;font-family:
  "Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;mso-themecolor:
  text1;mso-fareast-language:ZH-CN'>Είδος<o:p></o:p></span></p>
  </td>
  <td width=101 valign=top style='width:75.95pt;border:solid windowtext 1.0pt;
  border-left:none;mso-border-left-alt:solid windowtext .5pt;mso-border-alt:
  solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span style='font-size:12.0pt;font-family:
  "Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;mso-themecolor:
  text1;mso-fareast-language:ZH-CN'>Ποσότητα<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:1;height:16.5pt'>
  <td width=193 valign=top style='width:144.75pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span lang=EN-US style='font-size:12.0pt;
  font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;
  mso-themecolor:text1;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN'>Arduino
  UNO R3 SMD<o:p></o:p></span></p>
  </td>
  <td width=101 valign=top style='width:75.95pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span style='font-size:12.0pt;font-family:
  "Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;mso-themecolor:
  text1;mso-fareast-language:ZH-CN'>5<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:2;height:16.5pt'>
  <td width=193 valign=top style='width:144.75pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span lang=EN-US style='font-size:12.0pt;
  font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;
  mso-themecolor:text1;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN'>Ultrasonic
  distance sensor<o:p></o:p></span></p>
  </td>
  <td width=101 valign=top style='width:75.95pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span lang=EN-US style='font-size:12.0pt;
  font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;
  mso-themecolor:text1;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN'>5<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:3;height:16.5pt'>
  <td width=193 valign=top style='width:144.75pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span lang=EN-US style='font-size:12.0pt;
  font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;
  mso-themecolor:text1;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN'>9v
  Battery<o:p></o:p></span></p>
  </td>
  <td width=101 valign=top style='width:75.95pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span lang=EN-US style='font-size:12.0pt;
  font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;
  mso-themecolor:text1;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN'>5<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:4;height:16.5pt'>
  <td width=193 valign=top style='width:144.75pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span lang=EN-US style='font-size:12.0pt;
  font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;
  mso-themecolor:text1;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN'>Jumper
  wires 40pcs<o:p></o:p></span></p>
  </td>
  <td width=101 valign=top style='width:75.95pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span lang=EN-US style='font-size:12.0pt;
  font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;
  mso-themecolor:text1;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN'>5<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:5;height:16.5pt'>
  <td width=193 valign=top style='width:144.75pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span lang=EN-US style='font-size:12.0pt;
  font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;
  mso-themecolor:text1;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN'>LEDs
  <o:p></o:p></span></p>
  </td>
  <td width=101 valign=top style='width:75.95pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span lang=EN-US style='font-size:12.0pt;
  font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;
  mso-themecolor:text1;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN'>5<o:p></o:p></span></p>
  </td>
 </tr>
 <tr style='mso-yfti-irow:6;mso-yfti-lastrow:yes;height:16.5pt'>
  <td width=193 valign=top style='width:144.75pt;border:solid windowtext 1.0pt;
  border-top:none;mso-border-top-alt:solid windowtext .5pt;mso-border-alt:solid windowtext .5pt;
  padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span lang=EN-US style='font-size:12.0pt;
  font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;
  mso-themecolor:text1;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN'>Breadboard<o:p></o:p></span></p>
  </td>
  <td width=101 valign=top style='width:75.95pt;border-top:none;border-left:
  none;border-bottom:solid windowtext 1.0pt;border-right:solid windowtext 1.0pt;
  mso-border-top-alt:solid windowtext .5pt;mso-border-left-alt:solid windowtext .5pt;
  mso-border-alt:solid windowtext .5pt;padding:0cm 5.4pt 0cm 5.4pt;height:16.5pt'>
  <p class=MsoNormal style='margin-top:0cm;margin-right:11.3pt;margin-bottom:
  0cm;margin-left:0cm;margin-bottom:.0001pt;text-align:justify;text-justify:
  inter-ideograph;line-height:normal'><span lang=EN-US style='font-size:12.0pt;
  font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;
  mso-themecolor:text1;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN'>5<o:p></o:p></span></p>
  </td>
 </tr>
</table>

<p class=MsoNormal style='margin-right:11.3pt;text-align:justify;text-justify:
inter-ideograph;text-indent:36.0pt'><span style='font-size:12.0pt;line-height:
107%;font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;
mso-themecolor:text1;mso-fareast-language:ZH-CN'><o:p>&nbsp;</o:p></span></p>

<h1><a name="_Toc137899621"><span style='font-size:18.0pt;mso-bidi-font-size:
16.0pt;line-height:107%;mso-fareast-language:ZH-CN'>Στόχος </span></a><span
style='mso-bookmark:_Toc137899621'><span style='mso-fareast-language:ZH-CN'>Εφαρμογής</span></span><span
style='mso-fareast-language:ZH-CN'><o:p></o:p></span></h1>

<p class=MsoNormal style='margin-right:-19.15pt;text-indent:36.0pt'><span
style='font-size:12.0pt;line-height:107%;font-family:"Comic Sans MS";
mso-bidi-font-family:Helvetica;color:black;mso-themecolor:text1;mso-fareast-language:
ZH-CN'>Ο Στόχος αυτής της εφαρμογής είναι να διευκολύνει τους ανθρώπους που
μαζεύουν τα σκουπίδια ή ακόμα και τους ανθρώπους για να πετάξουν τα σκουπίδια τους.<o:p></o:p></span></p>

<h1><a name="_Toc137899622"><span style='mso-fareast-language:ZH-CN'>Προτεινόμενη
Λύση</span></a><span style='mso-fareast-language:ZH-CN'><o:p></o:p></span></h1>

<p class=MsoNormal style='margin-right:-19.15pt;text-align:justify;text-justify:
inter-ideograph;text-indent:36.0pt'><span style='font-size:12.0pt;line-height:
107%;font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;
mso-themecolor:text1;mso-fareast-language:ZH-CN'>Η πιλοτική εφαρμογή που
προτείνουμε να δημιουργήσαμε αποτελεί μια ιδέα που μπορεί να εξοικονομήσει
ενέργεια κατά τη αποκομιδή και διαχείριση των οικιακών αποβλήτων αλλά και να
δημιουργήσει ένα πιο φιλικό αστικό και βιώσιμο αστικό περιβάλλον, μειώνοντας
την σπατάλη ενέργειας, τον θόρυβο, την επιβάρυνση του κυκλοφοριακού φόρτου της
πόλης από την άσκοπη μετακίνηση μηχανημάτων αποκομιδής, όταν αυτό μπορεί να
προβλεφθεί και να αποφευχθεί.<o:p></o:p></span></p>

<p class=MsoNormal style='margin-right:-19.15pt;text-align:justify;text-justify:
inter-ideograph'><span style='font-size:12.0pt;line-height:107%;font-family:
"Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;mso-themecolor:text1;
mso-fareast-language:ZH-CN'>Αρχικά θα πρέπει πρώτα να εισάγουμε (ορίσουμε) το
ύψος του κάδου απορριμμάτων. Αυτό θα μας βοηθήσει να υπολογίσουμε το ποσοστό των
απορριμμάτων μέσα στον κάδο απορριμμάτων. Στη συνέχεια, έχουμε δύο κριτήρια που
πρέπει να πληρούνται για να δείξουμε ότι ο συγκεκριμένος κάδος πρέπει να
αδειάσει:<o:p></o:p></span></p>

<p class=MsoNormal style='margin-right:-19.15pt'><span style='font-size:12.0pt;
line-height:107%;font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;
color:black;mso-themecolor:text1;mso-fareast-language:ZH-CN'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraph style='margin-top:0cm;margin-right:-19.15pt;
margin-bottom:8.0pt;margin-left:14.2pt;mso-add-space:auto;text-align:justify;
text-justify:inter-ideograph;text-indent:-14.2pt;mso-list:l4 level1 lfo1'><![if !supportLists]><span
lang=EN-US style='font-size:12.0pt;line-height:107%;font-family:"Comic Sans MS";
mso-fareast-font-family:"Comic Sans MS";mso-bidi-font-family:"Comic Sans MS";
color:black;mso-themecolor:text1;mso-ansi-language:EN-US;mso-fareast-language:
ZH-CN'><span style='mso-list:Ignore'>1.<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;
</span></span></span><![endif]><span style='font-size:12.0pt;line-height:107%;
font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;
mso-themecolor:text1;mso-fareast-language:ZH-CN'>Ας πούμε ότι εάν ο κάδος σας
είναι μισογεμάτος, δεν χρειάζεται πραγματικά να τον αδειάσετε. Το σημείο
πλήρωσης του κάδου, ή η μέγιστη ποσότητα απορριμμάτων που επιτρέπουμε, είναι το
75% του κάδου. </span><span lang=EN-US style='font-size:12.0pt;line-height:
107%;font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;
mso-themecolor:text1;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN'>(Μπ<span
class=SpellE>ορείτε</span> να <span class=SpellE>οριστεί</span> α<span
class=SpellE>νάλογ</span>α <span class=SpellE>με</span> <span class=SpellE>τις</span>
επ<span class=SpellE>ιλογές</span> <span class=SpellE>του</span> <span
class=SpellE>χρήστη</span>.)<o:p></o:p></span></p>

<p class=MsoNormal style='margin-right:-19.15pt;text-align:justify;text-justify:
inter-ideograph'><span lang=EN-US style='font-size:12.0pt;line-height:107%;
font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;
mso-themecolor:text1;mso-ansi-language:EN-US;mso-fareast-language:ZH-CN'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpFirst style='margin-top:0cm;margin-right:-19.15pt;
margin-bottom:8.0pt;margin-left:14.2pt;mso-add-space:auto;text-align:justify;
text-justify:inter-ideograph;text-indent:-14.2pt;mso-list:l4 level1 lfo1'><![if !supportLists]><span
style='font-size:12.0pt;line-height:107%;font-family:"Comic Sans MS";
mso-fareast-font-family:"Comic Sans MS";mso-bidi-font-family:"Comic Sans MS";
color:black;mso-themecolor:text1;mso-fareast-language:ZH-CN'><span
style='mso-list:Ignore'>2.<span style='font:7.0pt "Times New Roman"'>&nbsp; </span></span></span><![endif]><span
style='font-size:12.0pt;line-height:107%;font-family:"Comic Sans MS";
mso-bidi-font-family:Helvetica;color:black;mso-themecolor:text1;mso-fareast-language:
ZH-CN'>Αν υποθέσουμε ότι ένας συγκεκριμένος κάδος απορριμμάτων γεμίζει 20% και
μετά για μια εβδομάδα δεν αλλάζει, μπαίνει στο δεύτερο κριτήριό μας, ο χρόνος.
Με τον καιρό, ακόμη και η μικρή ποσότητα θα αρχίσει να σαπίζει, οδηγώντας σε
ένα δύσοσμο περιβάλλον. Για να αποφύγουμε το επίπεδο ανοχής μας να είναι 2
ημέρες, επομένως εάν ένας κάδος απορριμμάτων είναι μικρότερος από 75% αλλά
είναι δύο ημερών, τότε θα πρέπει επίσης να αδειάσει.<o:p></o:p></span></p>

<p class=MsoListParagraphCxSpMiddle><span style='font-size:12.0pt;line-height:
107%;font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;
mso-themecolor:text1;mso-fareast-language:ZH-CN'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle><span style='font-size:12.0pt;line-height:
107%;font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;
mso-themecolor:text1;mso-fareast-language:ZH-CN'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle><span style='font-size:12.0pt;line-height:
107%;font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;
mso-themecolor:text1;mso-fareast-language:ZH-CN'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle><span style='font-size:12.0pt;line-height:
107%;font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;
mso-themecolor:text1;mso-fareast-language:ZH-CN'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpMiddle><span style='font-size:12.0pt;line-height:
107%;font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;
mso-themecolor:text1;mso-fareast-language:ZH-CN'><o:p>&nbsp;</o:p></span></p>

<p class=MsoListParagraphCxSpLast><span style='font-size:12.0pt;line-height:
107%;font-family:"Comic Sans MS";mso-bidi-font-family:Helvetica;color:black;
mso-themecolor:text1;mso-fareast-language:ZH-CN'><o:p>&nbsp;</o:p></span></p>

<h1><a name="_Toc137899623"><span style='mso-fareast-language:ZH-CN'>Σενάριο&nbsp;Δραστηριότητας</span></a><span
style='mso-fareast-language:ZH-CN'><o:p></o:p></span></h1>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><b style='mso-bidi-font-weight:normal'><span
style='font-family:"Comic Sans MS";mso-bidi-font-family:"Segoe UI";color:#1F2328'><o:p>&nbsp;</o:p></span></b></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";mso-bidi-font-family:
"Segoe UI";color:#1F2328'>Αριθμός μαθητών: 7<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";mso-bidi-font-family:
"Segoe UI";color:#1F2328'>Αριθμός ομάδων: 1<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";mso-bidi-font-family:
"Segoe UI";color:#1F2328'>Αριθμός Ατόμων ανά ομάδα: 7<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
7.1pt;text-indent:-7.1pt;background:white'><span style='font-family:"Comic Sans MS";
mso-bidi-font-family:"Segoe UI";color:#1F2328'>Είδος Δραστηριότητας:&nbsp;<span
class=SpellE>Ομαδοσυνεργατική</span><o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";mso-bidi-font-family:
"Segoe UI";color:#1F2328'>Ρόλοι: Δεν υπάρχουν διακριτοί ρόλοι στην ομάδα<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";mso-bidi-font-family:
"Segoe UI";color:#1F2328'>Ηλικιακή Ομάδα: 11-12<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";mso-bidi-font-family:
"Segoe UI";color:#1F2328'><o:p>&nbsp;</o:p></span></p>

<h1><a name="_Toc137899624"><span style='mso-fareast-language:ZH-CN'>Φάση
Προετοιμασίας</span></a><span style='mso-fareast-language:ZH-CN'><o:p></o:p></span></h1>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";mso-bidi-font-family:
"Segoe UI";color:#1F2328'>Οι μαθητές:<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
36.0pt;text-indent:-18.0pt;mso-list:l5 level1 lfo5;background:white'><![if !supportLists]><span
style='font-family:Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:
Symbol;color:#1F2328'><span style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span style='font-family:"Comic Sans MS";
mso-bidi-font-family:"Segoe UI";color:#1F2328'>Βρήκαμε&nbsp;την&nbsp;ιδέα<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
36.0pt;text-indent:-18.0pt;mso-list:l5 level1 lfo5;background:white'><![if !supportLists]><span
style='font-family:Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:
Symbol;color:#1F2328'><span style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span style='font-family:"Comic Sans MS";
mso-bidi-font-family:"Segoe UI";color:#1F2328'>Ορίσαμε&nbsp;τις&nbsp;προδιαγραφές&nbsp;της&nbsp;εφαρμογής<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
36.0pt;text-indent:-18.0pt;mso-list:l5 level1 lfo5;background:white'><![if !supportLists]><span
style='font-family:Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:
Symbol;color:#1F2328'><span style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span style='font-family:"Comic Sans MS";
mso-bidi-font-family:"Segoe UI";color:#1F2328'>Σκεφτήκαμε&nbsp;τις&nbsp;λειτουργίες&nbsp;της&nbsp;εφαρμογής<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
36.0pt;text-indent:-18.0pt;mso-list:l5 level1 lfo5;background:white'><![if !supportLists]><span
style='font-family:Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:
Symbol;color:#1F2328'><span style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span style='font-family:"Comic Sans MS";
mso-bidi-font-family:"Segoe UI";color:#1F2328'>Καταγράψαμε&nbsp;τις&nbsp;ανάγκες&nbsp;για&nbsp;υλικά<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
36.0pt;text-indent:-18.0pt;mso-list:l5 level1 lfo5;background:white'><![if !supportLists]><span
style='font-family:Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:
Symbol;color:#1F2328'><span style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span style='font-family:"Comic Sans MS";
mso-bidi-font-family:"Segoe UI";color:#1F2328'>Παραγγείλαμε τα&nbsp;υλικά<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
36.0pt;text-indent:-18.0pt;mso-list:l5 level1 lfo5;background:white'><![if !supportLists]><span
style='font-family:Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:
Symbol;color:#1F2328'><span style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span style='font-family:"Comic Sans MS";
mso-bidi-font-family:"Segoe UI";color:#1F2328'>Προετοιμάσαμε και αποστείλαμε την
περίληψη για την συμμετοχή μας στον διαγωνισμό<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";mso-bidi-font-family:
"Segoe UI";color:#1F2328'><o:p>&nbsp;</o:p></span></p>

<h1><a name="_Toc137899625">Φάση σχεδιασμού</a></h1>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";mso-bidi-font-family:
"Segoe UI";color:#1F2328'>Η συσκευή που θέλουμε να φτιάξουμε θα είναι φτιαγμένη
από έναν αισθητήρα απόστασης (</span><span lang=EN-GB style='font-family:"Comic Sans MS";
mso-bidi-font-family:"Segoe UI";color:#1F2328;mso-ansi-language:EN-GB'>ultrasonic</span><span
lang=EN-GB style='font-family:"Comic Sans MS";mso-bidi-font-family:"Segoe UI";
color:#1F2328'> </span><span lang=EN-GB style='font-family:"Comic Sans MS";
mso-bidi-font-family:"Segoe UI";color:#1F2328;mso-ansi-language:EN-GB'>sensor</span><span
style='font-family:"Comic Sans MS";mso-bidi-font-family:"Segoe UI";color:#1F2328'>)
ο οποίος θα τοποθετηθεί στο καπάκι του κάδου και θα μετράει την ποσότητα των
σκουπιδιών στον κάδο. Το μηχάνημα θα ελέγχετε από το </span><span lang=EN-GB
style='font-family:"Comic Sans MS";mso-bidi-font-family:"Segoe UI";color:#1F2328;
mso-ansi-language:EN-GB'>Arduino</span><span lang=EN-GB style='font-family:
"Comic Sans MS";mso-bidi-font-family:"Segoe UI";color:#1F2328'> </span><span
lang=EN-GB style='font-family:"Comic Sans MS";mso-bidi-font-family:"Segoe UI";
color:#1F2328;mso-ansi-language:EN-GB'>Uno</span><span lang=EN-GB
style='font-family:"Comic Sans MS";mso-bidi-font-family:"Segoe UI";color:#1F2328'>
</span><span lang=EN-GB style='font-family:"Comic Sans MS";mso-bidi-font-family:
"Segoe UI";color:#1F2328;mso-ansi-language:EN-GB'>R</span><span
style='font-family:"Comic Sans MS";mso-bidi-font-family:"Segoe UI";color:#1F2328'>3.<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";mso-bidi-font-family:
"Segoe UI";color:#1F2328'><o:p>&nbsp;</o:p></span></p>

<h1><a name="_Toc137899626">Δυσκολίες που αντιμετωπίσαμε</a></h1>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";mso-bidi-font-family:
"Segoe UI";color:#1F2328'>Ήταν αρκετά δύσκολο να δούμε πως συνδέεται το κάθε
καλώδιο και το πως να το συνδέσουμε με το </span><span lang=EN-GB
style='font-family:"Comic Sans MS";mso-bidi-font-family:"Segoe UI";color:#1F2328;
mso-ansi-language:EN-GB'>Arduino</span><span lang=EN-GB style='font-family:
"Comic Sans MS";mso-bidi-font-family:"Segoe UI";color:#1F2328'> </span><span
style='font-family:"Comic Sans MS";mso-bidi-font-family:"Segoe UI";color:#1F2328'>UNO.
Επίσης ήταν αρκετά δύσκολο να προσαρμόσουμε τον κώδικα για να ταιριάζει στα
δικά μας δεδομένα.<o:p></o:p></span></p>

<h1><a name="_Toc137899627">Σε τι μας βοηθάει</a></h1>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";mso-bidi-font-family:
"Segoe UI";color:#1F2328'>Η βοήθειά του είναι μεγάλη διότι όποιος θέλει να
αδειάσει τον κάδο θα μπορεί απλώς να μπει στην εφαρμογή και να δει αν ο κάδος
είναι γεμάτος ή άδειος τότε θα τους διευκολύνει. Η εφαρμογή βοηθάει τους αυτούς
τους φορείς, </span><span style='font-family:"Comic Sans MS";mso-fareast-font-family:
DengXian;mso-fareast-theme-font:minor-fareast;mso-bidi-font-family:"Segoe UI";
color:#1F2328'>Όπως ο Δήμος, η περιφέρεια και η γειτονιά.</span><span
style='font-family:"Comic Sans MS";mso-bidi-font-family:"Segoe UI";color:#1F2328'>
</span><span style='font-family:DengXian;mso-ascii-theme-font:minor-fareast;
mso-fareast-theme-font:minor-fareast;mso-hansi-theme-font:minor-fareast;
mso-bidi-font-family:"Segoe UI";color:#1F2328'>Γ</span><span style='font-family:
"Comic Sans MS";mso-bidi-font-family:"Segoe UI";color:#1F2328'>λυτώνει πολύ
χρόνο.<o:p></o:p></span></p>

<h1><!--[if gte vml 1]><v:shapetype id="_x0000_t202" coordsize="21600,21600"
 o:spt="202" path="m,l,21600r21600,l21600,xe">
 <v:stroke joinstyle="miter"/>
 <v:path gradientshapeok="t" o:connecttype="rect"/>
</v:shapetype><v:shape id="Πλαίσιο_x0020_κειμένου_x0020_2" o:spid="_x0000_s1026"
 type="#_x0000_t202" style='position:absolute;margin-left:404.8pt;margin-top:55.2pt;
 width:456pt;height:209.25pt;z-index:251662336;visibility:visible;
 mso-wrap-style:square;mso-width-percent:0;mso-height-percent:0;
 mso-wrap-distance-left:9pt;mso-wrap-distance-top:3.6pt;
 mso-wrap-distance-right:9pt;mso-wrap-distance-bottom:3.6pt;
 mso-position-horizontal:right;mso-position-horizontal-relative:margin;
 mso-position-vertical:absolute;mso-position-vertical-relative:text;
 mso-width-percent:0;mso-height-percent:0;mso-width-relative:margin;
 mso-height-relative:margin;v-text-anchor:top' o:gfxdata="UEsDBBQABgAIAAAAIQC2gziS/gAAAOEBAAATAAAAW0NvbnRlbnRfVHlwZXNdLnhtbJSRQU7DMBBF
90jcwfIWJU67QAgl6YK0S0CoHGBkTxKLZGx5TGhvj5O2G0SRWNoz/78nu9wcxkFMGNg6quQqL6RA
0s5Y6ir5vt9lD1JwBDIwOMJKHpHlpr69KfdHjyxSmriSfYz+USnWPY7AufNIadK6MEJMx9ApD/oD
OlTrorhX2lFEilmcO2RdNtjC5xDF9pCuTyYBB5bi6bQ4syoJ3g9WQ0ymaiLzg5KdCXlKLjvcW893
SUOqXwnz5DrgnHtJTxOsQfEKIT7DmDSUCaxw7Rqn8787ZsmRM9e2VmPeBN4uqYvTtW7jvijg9N/y
JsXecLq0q+WD6m8AAAD//wMAUEsDBBQABgAIAAAAIQA4/SH/1gAAAJQBAAALAAAAX3JlbHMvLnJl
bHOkkMFqwzAMhu+DvYPRfXGawxijTi+j0GvpHsDYimMaW0Yy2fr2M4PBMnrbUb/Q94l/f/hMi1qR
JVI2sOt6UJgd+ZiDgffL8ekFlFSbvV0oo4EbChzGx4f9GRdb25HMsYhqlCwG5lrLq9biZkxWOiqY
22YiTra2kYMu1l1tQD30/bPm3wwYN0x18gb45AdQl1tp5j/sFB2T0FQ7R0nTNEV3j6o9feQzro1i
OWA14Fm+Q8a1a8+Bvu/d/dMb2JY5uiPbhG/ktn4cqGU/er3pcvwCAAD//wMAUEsDBBQABgAIAAAA
IQAyw/IKTwIAAF4EAAAOAAAAZHJzL2Uyb0RvYy54bWysVM2O0zAQviPxDpbvNE3UbrdR09XSpQhp
+ZEWHsB1nMbC8QTbbbJc0b4HL4AQBw78ad8g+0qMnW4pfxdEDtaMx/PNzDczmZ20lSJbYawEndF4
MKREaA651OuMvni+vHdMiXVM50yBFhm9FJaezO/emTV1KhIoQeXCEATRNm3qjJbO1WkUWV6KitkB
1EKjsQBTMYeqWUe5YQ2iVypKhsOjqAGT1wa4sBZvz3ojnQf8ohDcPS0KKxxRGcXcXDhNOFf+jOYz
lq4Nq0vJd2mwf8iiYlJj0D3UGXOMbIz8DaqS3ICFwg04VBEUheQi1IDVxMNfqrkoWS1CLUiOrfc0
2f8Hy59snxki84wm8YQSzSpsUve2+9J96N7fvOk+ddek+9x9ROFr96771l3fXJHE09bUNkXvixr9
XXsfWmx/oMDW58BfWqJhUTK9FqfGQFMKlmPasfeMDlx7HOtBVs1jyDE62zgIQG1hKs8pskQQHdt3
uW+ZaB3heDmeTGOcA0o42pKj8WQ0GYcYLL11r411DwVUxAsZNTgTAZ5tz63z6bD09omPZkHJfCmV
CopZrxbKkC3D+VmGb4f+0zOlSZPR6TgZ9wz8FWIYvj9BVNLhIihZZfR4/4ilnrcHOg9j6phUvYwp
K70j0nPXs+jaVbtrzAryS6TUQD/wuKAolGBeU9LgsGfUvtowIyhRjzS2ZRqPRn47gjIaTxJUzKFl
dWhhmiNURh0lvbhwYaM8YRpOsX2FDMT6PveZ7HLFIQ587xbOb8mhHl79+C3MvwMAAP//AwBQSwME
FAAGAAgAAAAhAHe2KfjeAAAACAEAAA8AAABkcnMvZG93bnJldi54bWxMj8FOwzAQRO9I/IO1SFwQ
dRJKSUKcCiGB6A0Kgqsbb5OIeB1sNw1/z3KC486MZt9U69kOYkIfekcK0kUCAqlxpqdWwdvrw2UO
IkRNRg+OUME3BljXpyeVLo070gtO29gKLqFQagVdjGMpZWg6tDos3IjE3t55qyOfvpXG6yOX20Fm
SbKSVvfEHzo94n2Hzef2YBXky6fpI2yunt+b1X4o4sXN9PjllTo/m+9uQUSc418YfvEZHWpm2rkD
mSAGBTwkspomSxBsF2nGyk7BdZYXIOtK/h9Q/wAAAP//AwBQSwECLQAUAAYACAAAACEAtoM4kv4A
AADhAQAAEwAAAAAAAAAAAAAAAAAAAAAAW0NvbnRlbnRfVHlwZXNdLnhtbFBLAQItABQABgAIAAAA
IQA4/SH/1gAAAJQBAAALAAAAAAAAAAAAAAAAAC8BAABfcmVscy8ucmVsc1BLAQItABQABgAIAAAA
IQAyw/IKTwIAAF4EAAAOAAAAAAAAAAAAAAAAAC4CAABkcnMvZTJvRG9jLnhtbFBLAQItABQABgAI
AAAAIQB3tin43gAAAAgBAAAPAAAAAAAAAAAAAAAAAKkEAABkcnMvZG93bnJldi54bWxQSwUGAAAA
AAQABADzAAAAtAUAAAAA
">
 <v:textbox>
  <![if !mso]>
  <table cellpadding=0 cellspacing=0 width="100%">
   <tr>
    <td><![endif]>
    <div>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'>#include
    &lt;Software Serial.h&gt;<span style='mso-spacerun:yes'>   </span><o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'>#include
    &lt;ESP8266WiFi.h&gt;<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'>#include
    &lt;ESP8266HTTPClient.h&gt;<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><o:p>&nbsp;</o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'>#define
    trigger D5<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'>#define
    echo D6<span style='mso-spacerun:yes'>     </span><o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'>float
    times=0;<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'>int
    distance=0;<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'>//
    Replace with your network credentials<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'>const
    char* ssid<span style='mso-spacerun:yes'>     </span>= &quot;muthu&quot;;<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'>const
    char* password = &quot;muthumuthu001&quot;;<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><o:p>&nbsp;</o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><o:p>&nbsp;</o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'>void
    setup() {<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>  </span>Serial.begin(115200);<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>  </span>Serial.print(&quot;Connecting to &quot;);<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>  </span>Serial.println(ssid);<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>  </span>pinMode(trigger,OUTPUT);<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>  </span>pinMode(echo,INPUT);<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>  </span>WiFi.begin(ssid, password);<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>  </span>while (WiFi.status() != WL_CONNECTED) {<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>    </span>delay(500);<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>    </span>Serial.print(&quot;.&quot;);<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>  </span>}<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>  </span>Serial.println(&quot;&quot;);<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>  </span>Serial.println(&quot;WiFi
    connected.&quot;);<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>  </span>Serial.println(&quot;IP address: &quot;);<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>  </span>Serial.println(WiFi.localIP());<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><o:p>&nbsp;</o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'>}<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><o:p>&nbsp;</o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><o:p>&nbsp;</o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'>void
    loop() {<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><o:p>&nbsp;</o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>  </span>digitalWrite(trigger,LOW);<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'> </span>delayMicroseconds(2);<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'> </span>digitalWrite(trigger,HIGH);<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'> </span>delayMicroseconds(10);<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'> </span>digitalWrite(trigger,LOW);<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'> </span>delayMicroseconds(2);<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'> </span>times=pulseIn(echo,HIGH);<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'> </span>int distance=times*340/20000;<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><o:p>&nbsp;</o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'> </span>//Serial.println(&quot;Distance:&quot;);<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'> </span>Serial.println(distance);<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'> </span>//Serial.println(&quot; cm&quot;);<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>  </span>if (WiFi.status() == WL_CONNECTED) {
    //Check WiFi connection status<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'> </span><o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>    </span>HTTPClient http;<span
    style='mso-spacerun:yes'>  </span>//Declare an object of class HTTPClient<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>  </span><o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>   
    </span>http.begin(&quot;http://192.168.43.204/ultrasonic/data.php?cm=&quot;+String(distance));<span
    style='mso-spacerun:yes'>  </span>//Specify request destination<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>    </span><o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>    </span>int httpCode = http.GET();<span
    style='mso-spacerun:yes'>                                  </span>//Send
    the request<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>  </span><o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>    </span>if (httpCode &gt; 0) { //Check the returning
    code<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'> </span><o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>      </span>String payload =
    http.getString();<span style='mso-spacerun:yes'>   </span>//Get the request
    response payload<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>      </span>Serial.println(payload);<span
    style='mso-spacerun:yes'>             </span>//Print the response payload<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'> </span><o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>    </span>}<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'> </span><o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>    </span>http.end();<span
    style='mso-spacerun:yes'>   </span>//Close connection<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'> </span><o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>  </span>}<o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'> </span><o:p></o:p></span></p>
    <p class=MsoNormal><span lang=EN-US style='mso-ansi-language:EN-US'><span
    style='mso-spacerun:yes'>  </span>delay(1000);<span
    style='mso-spacerun:yes'>    </span>//Send a request every 30 seconds<o:p></o:p></span></p>
    <p class=MsoNormal>}</p>
    </div>
    <![if !mso]></td>
   </tr>
  </table>
  <![endif]></v:textbox>
 <w:wrap type="square" anchorx="margin"/>
</v:shape><![endif]--><![if !vml]><img width=613 height=284
src="Arduino_smart_garbadge_monitoring_system_2023_Readme1.files/image005.png"
align=right hspace=12 vspace=5
alt="Πλαίσιο κειμένου: #include &lt;Software Serial.h&gt;   &#13;&#10;#include &lt;ESP8266WiFi.h&gt;&#13;&#10;#include &lt;ESP8266HTTPClient.h&gt;&#13;&#10;&#13;&#10;#define trigger D5&#13;&#10;#define echo D6     &#13;&#10;float times=0;&#13;&#10;int distance=0;&#13;&#10;// Replace with your network credentials&#13;&#10;const char* ssid     = &quot;muthu&quot;;&#13;&#10;const char* password = &quot;muthumuthu001&quot;;&#13;&#10;&#13;&#10;&#13;&#10;void setup() {&#13;&#10;  Serial.begin(115200);&#13;&#10;  Serial.print(&quot;Connecting to &quot;);&#13;&#10;  Serial.println(ssid);&#13;&#10;  pinMode(trigger,OUTPUT);&#13;&#10;  pinMode(echo,INPUT);&#13;&#10;  WiFi.begin(ssid, password);&#13;&#10;  while (WiFi.status() != WL_CONNECTED) {&#13;&#10;    delay(500);&#13;&#10;    Serial.print(&quot;.&quot;);&#13;&#10;  }&#13;&#10;  Serial.println(&quot;&quot;);&#13;&#10;  Serial.println(&quot;WiFi connected.&quot;);&#13;&#10;  Serial.println(&quot;IP address: &quot;);&#13;&#10;  Serial.println(WiFi.localIP());&#13;&#10;&#13;&#10;}&#13;&#10;&#13;&#10;&#13;&#10;void loop() {&#13;&#10;&#13;&#10;  digitalWrite(trigger,LOW);&#13;&#10; delayMicroseconds(2);&#13;&#10; digitalWrite(trigger,HIGH);&#13;&#10; delayMicroseconds(10);&#13;&#10; digitalWrite(trigger,LOW);&#13;&#10; delayMicroseconds(2);&#13;&#10; times=pulseIn(echo,HIGH);&#13;&#10; int distance=times*340/20000;&#13;&#10;&#13;&#10; //Serial.println(&quot;Distance:&quot;);&#13;&#10; Serial.println(distance);&#13;&#10; //Serial.println(&quot; cm&quot;);&#13;&#10;  if (WiFi.status() == WL_CONNECTED) { //Check WiFi connection status&#13;&#10; &#13;&#10;    HTTPClient http;  //Declare an object of class HTTPClient&#13;&#10;  &#13;&#10;    http.begin(&quot;http://192.168.43.204/ultrasonic/data.php?cm=&quot;+String(distance));  //Specify request destination&#13;&#10;    &#13;&#10;    int httpCode = http.GET();                                  //Send the request&#13;&#10;  &#13;&#10;    if (httpCode &gt; 0) { //Check the returning code&#13;&#10; &#13;&#10;      String payload = http.getString();   //Get the request response payload&#13;&#10;      Serial.println(payload);             //Print the response payload&#13;&#10; &#13;&#10;    }&#13;&#10; &#13;&#10;    http.end();   //Close connection&#13;&#10; &#13;&#10;  }&#13;&#10; &#13;&#10;  delay(1000);    //Send a request every 30 seconds&#13;&#10;}&#13;&#10;"
v:shapes="Πλαίσιο_x0020_κειμένου_x0020_2"><![endif]><a name="_Toc137899628">Κώδικας
</a><span style='mso-bookmark:_Toc137899628'><span lang=EN-US style='mso-ansi-language:
EN-US'>Arduino</span><span lang=EN-US> </span></span><span style='mso-bookmark:
_Toc137899628'><span lang=EN-US style='mso-ansi-language:EN-US'>IDE</span></span><span
style='mso-spacerun:yes'>   </span></h1>

<p class=MsoNormal><span style='font-size:12.0pt;line-height:107%'><o:p>&nbsp;</o:p></span></p>

<h1><a name="_Toc137899629">Μελλοντικές εξελίξεις</a> </h1>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";mso-bidi-font-family:
"Segoe UI";color:#1F2328'>Θα θέλαμε πολύ το Project μας να δημοσιευτεί στον
Δήμο Καλαμαριάς και σε άλλους Δήμους φυσικά για να διευκολύνει όλους τους
εργάτες που δουλεύουν στα απορριμματοφόρα.<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";mso-bidi-font-family:
"Segoe UI";color:#1F2328'><o:p>&nbsp;</o:p></span></p>

<h1><a name="_Toc137899630">Πλατφόρμες που χρησιμοποιήθηκαν</a></h1>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
36.0pt;text-indent:-18.0pt;mso-list:l2 level1 lfo6;background:white'><![if !supportLists]><span
style='font-family:Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:
Symbol;color:#1F2328'><span style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span class=SpellE><span lang=EN-US
style='font-family:"Comic Sans MS";mso-bidi-font-family:"Segoe UI";color:#1F2328;
mso-ansi-language:EN-US'>Tinkerc</span></span><span lang=EN-GB
style='font-family:"Comic Sans MS";mso-bidi-font-family:"Segoe UI";color:#1F2328;
mso-ansi-language:EN-GB'>ad</span><span style='font-family:"Comic Sans MS";
mso-bidi-font-family:"Segoe UI";color:#1F2328'><o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
36.0pt;text-indent:-18.0pt;mso-list:l2 level1 lfo6;background:white'><![if !supportLists]><span
style='font-family:Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:
Symbol;color:#1F2328'><span style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-family:"Comic Sans MS";
mso-bidi-font-family:"Segoe UI";color:#1F2328;mso-ansi-language:EN-US'>Arduino
IDE</span><span style='font-family:"Comic Sans MS";mso-bidi-font-family:"Segoe UI";
color:#1F2328'><o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
36.0pt;text-indent:-18.0pt;mso-list:l2 level1 lfo6;background:white'><![if !supportLists]><span
style='font-family:Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:
Symbol;color:#1F2328'><span style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span lang=EN-US style='font-family:"Comic Sans MS";
mso-bidi-font-family:"Segoe UI";color:#1F2328;mso-ansi-language:EN-US'>Prezi</span><span
style='font-family:"Comic Sans MS";mso-bidi-font-family:"Segoe UI";color:#1F2328'><o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
36.0pt;text-indent:-18.0pt;mso-list:l2 level1 lfo6;background:white'><![if !supportLists]><span
style='font-family:Symbol;mso-fareast-font-family:Symbol;mso-bidi-font-family:
Symbol;color:#1F2328'><span style='mso-list:Ignore'>·<span style='font:7.0pt "Times New Roman"'>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</span></span></span><![endif]><span class=SpellE><span lang=EN-US
style='font-family:"Comic Sans MS";mso-bidi-font-family:"Segoe UI";color:#1F2328;
mso-ansi-language:EN-US'>Appinventor</span></span><span style='font-family:
"Comic Sans MS";mso-bidi-font-family:"Segoe UI";color:#1F2328'><o:p></o:p></span></p>

<h1><a name="_Toc137899631">Υλοποίηση</a></h1>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";mso-bidi-font-family:
"Segoe UI";color:#1F2328'>Η συσκευή φτιάχτηκε συνδέοντας το </span><span
lang=EN-US style='font-family:"Comic Sans MS";mso-bidi-font-family:"Segoe UI";
color:#1F2328;mso-ansi-language:EN-US'>Arduino</span><span lang=EN-US
style='font-family:"Comic Sans MS";mso-bidi-font-family:"Segoe UI";color:#1F2328'>
</span><span style='font-family:"Comic Sans MS";mso-bidi-font-family:"Segoe UI";
color:#1F2328'>με τον Αισθητήρα <span style='mso-spacerun:yes'> </span></span><span
lang=EN-US style='font-family:"Comic Sans MS";mso-bidi-font-family:"Segoe UI";
color:#1F2328;mso-ansi-language:EN-US'>Ultrasonic</span><span lang=EN-US
style='font-family:"Comic Sans MS";mso-bidi-font-family:"Segoe UI";color:#1F2328'>
</span><span lang=EN-US style='font-family:"Comic Sans MS";mso-bidi-font-family:
"Segoe UI";color:#1F2328;mso-ansi-language:EN-US'>sensor</span><span
lang=EN-US style='font-family:"Comic Sans MS";mso-bidi-font-family:"Segoe UI";
color:#1F2328'> </span><span style='font-family:"Comic Sans MS";mso-bidi-font-family:
"Segoe UI";color:#1F2328'>και τα </span><span lang=EN-US style='font-family:
"Comic Sans MS";mso-bidi-font-family:"Segoe UI";color:#1F2328;mso-ansi-language:
EN-US'>LEDs</span><span style='font-family:"Comic Sans MS";mso-bidi-font-family:
"Segoe UI";color:#1F2328'>. Στη συνέχεια τα βάλαμε όλα μέσα στο κουτί και τα τοποθετήσαμε
στον κάδο.<o:p></o:p></span></p>

<h1><a name="_Toc137899632">Φάση Δοκιμών</a></h1>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";mso-bidi-font-family:
"Segoe UI";color:#1F2328'>Όταν το κύκλωμα ήταν έτοιμο έπρεπε να δούμε αν δούλευε.
Όταν κάναμε τις δύο τρείς πρώτες δοκιμές δεν ήμασταν και τόσο ευχαριστημένοι.
Όμως αργότερα όταν έγιναν κάποιες από αυτές είμασταν περισσότερο
ευχαριστημένοι. Κάποια από τα λαμπάκια μερικές φορές άναβαν ενώ κάποιες άλλες
όχι. Όταν πήγαινες πολύ κοντά το αντικείμενο, στον αισθητήρα,<span
style='mso-spacerun:yes'>  </span>τότε άναβε το κόκκινο λαμπάκι, αν το πήγαινες
λίγο πιο μακριά άναβε το μπλε, αν ήταν μακριά στο ένα μέτρο άναβε το πράσινο
και αν ήταν μακριά από ένα μέτρο τότε δεν άναβε κανένα λαμπάκι. <o:p></o:p></span></p>

<h1><a name="_Toc137899633">Συμπεράσματα</a> </h1>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";mso-bidi-font-family:
"Segoe UI";color:#1F2328'>Καταλάβαμε πόσο δύσκολο ήταν να αναλαμβάνεις κάτι
τόσο μεγάλο γιατί είμαστε ακόμα πολύ μικροί για να το καταλάβουμε και δεν
μπορούμε να φτιάξουμε ολόσωστα αυτό το </span><span lang=EN-US
style='font-family:"Comic Sans MS";mso-bidi-font-family:"Segoe UI";color:#1F2328;
mso-ansi-language:EN-US'>Project</span><span style='font-family:"Comic Sans MS";
mso-bidi-font-family:"Segoe UI";color:#1F2328'>.<o:p></o:p></span></p>

<p style='margin-top:0cm;margin-right:0cm;margin-bottom:12.0pt;margin-left:
0cm;background:white'><span style='font-family:"Comic Sans MS";mso-bidi-font-family:
"Segoe UI";color:#1F2328'><o:p>&nbsp;</o:p></span></p>

</div>

</body>

</html>
