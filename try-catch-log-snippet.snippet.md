# codesnipets
This project is all about creating custom visual studio code snippets.

<CodeSnippet Format="1.0.0">
    <Header>
        <Author>Venkata Krishna Ravula</Author>
        <Title>trycatchlog</Title>
               <Shortcut>trycatchlog</Shortcut>
        <SnippetTypes>
    <SnippetType>Expansion</SnippetType>
    <SnippetType>SurroundsWith</SnippetType>
   </SnippetTypes>
    </Header>
    <Snippet>
        <Declarations>
            <Literal>
                <ID>try_modifier</ID>
                <Default>try</Default>
            </Literal>
            <Literal>
                <ID>return_type</ID>
                <Default>void</Default>
            </Literal>
            <Literal>
                <ID>name</ID>
                <Default>New_method</Default>
            </Literal>
        </Declarations>
        <Code Language="csharp">
            <![CDATA[try
		   {
    
		   }
		   catch(Exception ex)
		   {
			    Logger.LogError(ex);
   
   	           }
]]>
        </Code>
    </Snippet>
</CodeSnippet>