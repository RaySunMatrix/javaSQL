# ava.sql (Java Platform SE 8 )
<noscript>
<div>JavaScript is disabled on your browser.</div>
</noscript>
<!-- ========= START OF TOP NAVBAR ======= -->
<div class="topNav"><a name="navbar.top">
<!--   -->
</a>
<div class="skipNav"><a href="#skip.navbar.top" title="Skip navigation links">Skip navigation links</a></div>
<a name="navbar.top.firstrow">
<!--   -->
</a>
<ul class="navList" title="Navigation">
<li><a href="https://docs.oracle.com/javase/8/docs/api/overview-summary.html">Overview</a></li>
<li class="navBarCell1Rev">Package</li>
<li>Class</li>
<li><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/package-use.html">Use</a></li>
<li><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/package-tree.html">Tree</a></li>
<li><a href="https://docs.oracle.com/javase/8/docs/api/deprecated-list.html">Deprecated</a></li>
<li><a href="https://docs.oracle.com/javase/8/docs/api/index-files/index-1.html">Index</a></li>
<li><a href="https://docs.oracle.com/javase/8/docs/api/help-doc.html">Help</a></li>
</ul>
<div class="aboutLanguage"><strong>Java�&nbsp;Platform<br>Standard&nbsp;Ed.&nbsp;8</strong></div>
</div>
<div class="subNav">
<ul class="navList">
<li><a href="https://docs.oracle.com/javase/8/docs/api/java/security/spec/package-summary.html">Prev&nbsp;Package</a></li>
<li><a href="https://docs.oracle.com/javase/8/docs/api/java/text/package-summary.html">Next&nbsp;Package</a></li>
</ul>
<ul class="navList">
<li><a href="https://docs.oracle.com/javase/8/docs/api/index.html?java/sql/package-summary.html" target="_top">Frames</a></li>
<li><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/package-summary.html" target="_top">No&nbsp;Frames</a></li>
</ul>
<ul class="navList" id="allclasses_navbar_top" style="display: block;">
<li><a href="https://docs.oracle.com/javase/8/docs/api/allclasses-noframe.html">All&nbsp;Classes</a></li>
</ul>
<div>
<script type="text/javascript">
  allClassesLink = document.getElementById("allclasses_navbar_top");
  if(window==top) {
    allClassesLink.style.display = "block";
  }
  else {
    allClassesLink.style.display = "none";
  }
  
</script>
</div>
<a name="skip.navbar.top">
<!--   -->
</a></div>
<!-- ========= END OF TOP NAVBAR ========= -->
<div class="header">
<h1 title="Package" class="title">Package&nbsp;java.sql</h1>
<div class="docSummary">
<div class="block">Provides the API for accessing and processing data stored in a 
data source (usually a relational database) using the 
Java<sup><font size="-2">TM</font></sup> programming language.</div>
</div>
<p>See:&nbsp;<a href="#package.description">Description</a></p>
</div>
<div class="contentContainer">
<ul class="blockList">
<li class="blockList">
<table class="typeSummary" border="0" cellpadding="3" cellspacing="0" summary="Interface Summary table, listing interfaces, and an explanation">
<caption><span>Interface Summary</span><span class="tabEnd">&nbsp;</span></caption>
<tbody><tr>
<th class="colFirst" scope="col">Interface</th>
<th class="colLast" scope="col">Description</th>
</tr>
</tbody><tbody>
<tr class="altColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/Array.html" title="interface in java.sql">Array</a></td>
<td class="colLast">
<div class="block">The mapping in the Java programming language for the SQL type
 <code>ARRAY</code>.</div>
</td>
</tr>
<tr class="rowColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/Blob.html" title="interface in java.sql">Blob</a></td>
<td class="colLast">
<div class="block">The representation (mapping) in
 the Java� programming
 language of an SQL
 <code>BLOB</code> value.</div>
</td>
</tr>
<tr class="altColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/CallableStatement.html" title="interface in java.sql">CallableStatement</a></td>
<td class="colLast">
<div class="block">The interface used to execute SQL stored procedures.</div>
</td>
</tr>
<tr class="rowColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/Clob.html" title="interface in java.sql">Clob</a></td>
<td class="colLast">
<div class="block">The mapping in the Java� programming language
 for the SQL <code>CLOB</code> type.</div>
</td>
</tr>
<tr class="altColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/Connection.html" title="interface in java.sql">Connection</a></td>
<td class="colLast">
<div class="block">A connection (session) with a specific
 database.</div>
</td>
</tr>
<tr class="rowColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/DatabaseMetaData.html" title="interface in java.sql">DatabaseMetaData</a></td>
<td class="colLast">
<div class="block">Comprehensive information about the database as a whole.</div>
</td>
</tr>
<tr class="altColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/Driver.html" title="interface in java.sql">Driver</a></td>
<td class="colLast">
<div class="block">The interface that every driver class must implement.</div>
</td>
</tr>
<tr class="rowColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/DriverAction.html" title="interface in java.sql">DriverAction</a></td>
<td class="colLast">
<div class="block">An interface that must be implemented when a <a href="https://docs.oracle.com/javase/8/docs/api/java/sql/Driver.html" title="interface in java.sql">Driver</a> wants to be
 notified by <code>DriverManager</code>.</div>
</td>
</tr>
<tr class="altColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/NClob.html" title="interface in java.sql">NClob</a></td>
<td class="colLast">
<div class="block">The mapping in the Java� programming language
 for the SQL <code>NCLOB</code> type.</div>
</td>
</tr>
<tr class="rowColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/ParameterMetaData.html" title="interface in java.sql">ParameterMetaData</a></td>
<td class="colLast">
<div class="block">An object that can be used to get information about the types
 and properties for each parameter marker in a
 <code>PreparedStatement</code> object.</div>
</td>
</tr>
<tr class="altColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/PreparedStatement.html" title="interface in java.sql">PreparedStatement</a></td>
<td class="colLast">
<div class="block">An object that represents a precompiled SQL statement.</div>
</td>
</tr>
<tr class="rowColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/Ref.html" title="interface in java.sql">Ref</a></td>
<td class="colLast">
<div class="block">The mapping in the Java programming language of an SQL <code>REF</code>
 value, which is a reference to an SQL structured type value in the database.</div>
</td>
</tr>
<tr class="altColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/ResultSet.html" title="interface in java.sql">ResultSet</a></td>
<td class="colLast">
<div class="block">A table of data representing a database result set, which
 is usually generated by executing a statement that queries the database.</div>
</td>
</tr>
<tr class="rowColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/ResultSetMetaData.html" title="interface in java.sql">ResultSetMetaData</a></td>
<td class="colLast">
<div class="block">An object that can be used to get information about the types
 and properties of the columns in a <code>ResultSet</code> object.</div>
</td>
</tr>
<tr class="altColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/RowId.html" title="interface in java.sql">RowId</a></td>
<td class="colLast">
<div class="block">The representation (mapping) in the Java programming language of an SQL ROWID
 value.</div>
</td>
</tr>
<tr class="rowColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/Savepoint.html" title="interface in java.sql">Savepoint</a></td>
<td class="colLast">
<div class="block">The representation of a savepoint, which is a point within
 the current transaction that can be referenced from the
 <code>Connection.rollback</code> method.</div>
</td>
</tr>
<tr class="altColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLData.html" title="interface in java.sql">SQLData</a></td>
<td class="colLast">
<div class="block">The interface used for the custom mapping of an SQL user-defined type (UDT) to
 a class in the Java programming language.</div>
</td>
</tr>
<tr class="rowColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLInput.html" title="interface in java.sql">SQLInput</a></td>
<td class="colLast">
<div class="block">An input stream that contains a stream of values representing an
 instance of an SQL structured type or an SQL distinct type.</div>
</td>
</tr>
<tr class="altColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLOutput.html" title="interface in java.sql">SQLOutput</a></td>
<td class="colLast">
<div class="block">The output stream for writing the attributes of a user-defined
 type back to the database.</div>
</td>
</tr>
<tr class="rowColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLType.html" title="interface in java.sql">SQLType</a></td>
<td class="colLast">
<div class="block">An object that is used to identify a generic SQL type, called a JDBC type or
 a vendor specific data type.</div>
</td>
</tr>
<tr class="altColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLXML.html" title="interface in java.sql">SQLXML</a></td>
<td class="colLast">
<div class="block">The mapping in the JavaTM programming language for the SQL XML type.</div>
</td>
</tr>
<tr class="rowColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/Statement.html" title="interface in java.sql">Statement</a></td>
<td class="colLast">
<div class="block">The object used for executing a static SQL statement
 and returning the results it produces.</div>
</td>
</tr>
<tr class="altColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/Struct.html" title="interface in java.sql">Struct</a></td>
<td class="colLast">
<div class="block">The standard mapping in the Java programming language for an SQL
 structured type.</div>
</td>
</tr>
<tr class="rowColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/Wrapper.html" title="interface in java.sql">Wrapper</a></td>
<td class="colLast">
<div class="block">Interface for JDBC classes which provide the ability to retrieve the delegate instance when the instance
 in question is in fact a proxy class.</div>
</td>
</tr>
</tbody>
</table>
</li>
<li class="blockList">
<table class="typeSummary" border="0" cellpadding="3" cellspacing="0" summary="Class Summary table, listing classes, and an explanation">
<caption><span>Class Summary</span><span class="tabEnd">&nbsp;</span></caption>
<tbody><tr>
<th class="colFirst" scope="col">Class</th>
<th class="colLast" scope="col">Description</th>
</tr>
</tbody><tbody>
<tr class="altColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/Date.html" title="class in java.sql">Date</a></td>
<td class="colLast">
<div class="block">A thin wrapper around a millisecond value that allows
 JDBC to identify this as an SQL <code>DATE</code> value.</div>
</td>
</tr>
<tr class="rowColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/DriverManager.html" title="class in java.sql">DriverManager</a></td>
<td class="colLast">
<div class="block">The basic service for managing a set of JDBC drivers.<br>
 <b>NOTE:</b> The <a href="https://docs.oracle.com/javase/8/docs/api/javax/sql/DataSource.html" title="interface in javax.sql"><code>DataSource</code></a> interface, new in the
 JDBC 2.0 API, provides another way to connect to a data source.</div>
</td>
</tr>
<tr class="altColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/DriverPropertyInfo.html" title="class in java.sql">DriverPropertyInfo</a></td>
<td class="colLast">
<div class="block">Driver properties for making a connection.</div>
</td>
</tr>
<tr class="rowColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLPermission.html" title="class in java.sql">SQLPermission</a></td>
<td class="colLast">
<div class="block">The permission for which the <code>SecurityManager</code> will check
 when code that is running an application with a
 <code>SecurityManager</code> enabled, calls the
 <code>DriverManager.deregisterDriver</code> method,
 <code>DriverManager.setLogWriter</code> method,
 <code>DriverManager.setLogStream</code> (deprecated) method,
 <code>SyncFactory.setJNDIContext</code> method,
 <code>SyncFactory.setLogger</code> method,
 <code>Connection.setNetworktimeout</code> method,
 or the <code>Connection.abort</code> method.</div>
</td>
</tr>
<tr class="altColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/Time.html" title="class in java.sql">Time</a></td>
<td class="colLast">
<div class="block">A thin wrapper around the <code>java.util.Date</code> class that allows the JDBC
 API to identify this as an SQL <code>TIME</code> value.</div>
</td>
</tr>
<tr class="rowColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/Timestamp.html" title="class in java.sql">Timestamp</a></td>
<td class="colLast">
<div class="block">A thin wrapper around <code>java.util.Date</code> that allows
 the JDBC API to identify this as an SQL <code>TIMESTAMP</code> value.</div>
</td>
</tr>
<tr class="altColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/Types.html" title="class in java.sql">Types</a></td>
<td class="colLast">
<div class="block">The class that defines the constants that are used to identify generic
 SQL types, called JDBC types.</div>
</td>
</tr>
</tbody>
</table>
</li>
<li class="blockList">
<table class="typeSummary" border="0" cellpadding="3" cellspacing="0" summary="Enum Summary table, listing enums, and an explanation">
<caption><span>Enum Summary</span><span class="tabEnd">&nbsp;</span></caption>
<tbody><tr>
<th class="colFirst" scope="col">Enum</th>
<th class="colLast" scope="col">Description</th>
</tr>
</tbody><tbody>
<tr class="altColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/ClientInfoStatus.html" title="enum in java.sql">ClientInfoStatus</a></td>
<td class="colLast">
<div class="block">Enumeration for status of the reason that a property could not be set
 via a call to <code>Connection.setClientInfo</code></div>
</td>
</tr>
<tr class="rowColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/JDBCType.html" title="enum in java.sql">JDBCType</a></td>
<td class="colLast">
<div class="block">Defines the constants that are used to identify generic
 SQL types, called JDBC types.</div>
</td>
</tr>
<tr class="altColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/PseudoColumnUsage.html" title="enum in java.sql">PseudoColumnUsage</a></td>
<td class="colLast">
<div class="block">Enumeration for pseudo/hidden column usage.</div>
</td>
</tr>
<tr class="rowColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/RowIdLifetime.html" title="enum in java.sql">RowIdLifetime</a></td>
<td class="colLast">
<div class="block">Enumeration for RowId life-time values.</div>
</td>
</tr>
</tbody>
</table>
</li>
<li class="blockList">
<table class="typeSummary" border="0" cellpadding="3" cellspacing="0" summary="Exception Summary table, listing exceptions, and an explanation">
<caption><span>Exception Summary</span><span class="tabEnd">&nbsp;</span></caption>
<tbody><tr>
<th class="colFirst" scope="col">Exception</th>
<th class="colLast" scope="col">Description</th>
</tr>
</tbody><tbody>
<tr class="altColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/BatchUpdateException.html" title="class in java.sql">BatchUpdateException</a></td>
<td class="colLast">
<div class="block">The subclass of <a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLException.html" title="class in java.sql"><code>SQLException</code></a> thrown when an error
 occurs during a batch update operation.</div>
</td>
</tr>
<tr class="rowColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/DataTruncation.html" title="class in java.sql">DataTruncation</a></td>
<td class="colLast">
<div class="block">An exception  thrown as a <code>DataTruncation</code> exception
 (on writes) or reported as a
 <code>DataTruncation</code> warning (on reads)
  when a data values is unexpectedly truncated for reasons other than its having
  exceeded <code>MaxFieldSize</code>.</div>
</td>
</tr>
<tr class="altColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLClientInfoException.html" title="class in java.sql">SQLClientInfoException</a></td>
<td class="colLast">
<div class="block">The subclass of <a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLException.html" title="class in java.sql"><code>SQLException</code></a> is thrown when one or more client info properties
 could not be set on a <code>Connection</code>.</div>
</td>
</tr>
<tr class="rowColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLDataException.html" title="class in java.sql">SQLDataException</a></td>
<td class="colLast">
<div class="block">The subclass of <a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLException.html" title="class in java.sql"><code>SQLException</code></a> thrown when the SQLState class value
 is '<i>22</i>', or under vendor-specified conditions.</div>
</td>
</tr>
<tr class="altColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLException.html" title="class in java.sql">SQLException</a></td>
<td class="colLast">
<div class="block">An exception that provides information on a database access
 error or other errors.</div>
</td>
</tr>
<tr class="rowColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLFeatureNotSupportedException.html" title="class in java.sql">SQLFeatureNotSupportedException</a></td>
<td class="colLast">
<div class="block">The subclass of <a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLException.html" title="class in java.sql"><code>SQLException</code></a> thrown when the SQLState class value is '<i>0A</i>'
 ( the value is 'zero' A).</div>
</td>
</tr>
<tr class="altColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLIntegrityConstraintViolationException.html" title="class in java.sql">SQLIntegrityConstraintViolationException</a></td>
<td class="colLast">
<div class="block">The subclass of <a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLException.html" title="class in java.sql"><code>SQLException</code></a> thrown when the SQLState class value
 is '<i>23</i>', or under vendor-specified conditions.</div>
</td>
</tr>
<tr class="rowColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLInvalidAuthorizationSpecException.html" title="class in java.sql">SQLInvalidAuthorizationSpecException</a></td>
<td class="colLast">
<div class="block">The subclass of <a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLException.html" title="class in java.sql"><code>SQLException</code></a> thrown when the SQLState class value
 is '<i>28</i>', or under vendor-specified conditions.</div>
</td>
</tr>
<tr class="altColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLNonTransientConnectionException.html" title="class in java.sql">SQLNonTransientConnectionException</a></td>
<td class="colLast">
<div class="block">The subclass of <a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLException.html" title="class in java.sql"><code>SQLException</code></a> thrown for the SQLState
 class value '<i>08</i>', or under vendor-specified conditions.</div>
</td>
</tr>
<tr class="rowColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLNonTransientException.html" title="class in java.sql">SQLNonTransientException</a></td>
<td class="colLast">
<div class="block">The subclass of <a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLException.html" title="class in java.sql"><code>SQLException</code></a> thrown when an instance where a retry
 of the same operation would fail unless the cause of the <code>SQLException</code>
 is corrected.</div>
</td>
</tr>
<tr class="altColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLRecoverableException.html" title="class in java.sql">SQLRecoverableException</a></td>
<td class="colLast">
<div class="block">The subclass of <a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLException.html" title="class in java.sql"><code>SQLException</code></a> thrown in situations where a
 previously failed operation might be able to succeed if the application performs
  some recovery steps and retries the entire transaction or in the case of a
 distributed transaction, the transaction branch.</div>
</td>
</tr>
<tr class="rowColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLSyntaxErrorException.html" title="class in java.sql">SQLSyntaxErrorException</a></td>
<td class="colLast">
<div class="block">The subclass of <a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLException.html" title="class in java.sql"><code>SQLException</code></a> thrown when the SQLState class value
 is '<i>42</i>', or under vendor-specified conditions.</div>
</td>
</tr>
<tr class="altColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLTimeoutException.html" title="class in java.sql">SQLTimeoutException</a></td>
<td class="colLast">
<div class="block">The subclass of <a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLException.html" title="class in java.sql"><code>SQLException</code></a> thrown when the timeout specified by
 <code>Statement.setQueryTimeout</code>, <code>DriverManager.setLoginTimeout</code>,
 <code>DataSource.setLoginTimeout</code>,<code>XADataSource.setLoginTimeout</code>
 has expired.</div>
</td>
</tr>
<tr class="rowColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLTransactionRollbackException.html" title="class in java.sql">SQLTransactionRollbackException</a></td>
<td class="colLast">
<div class="block">The subclass of <a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLException.html" title="class in java.sql"><code>SQLException</code></a> thrown when the SQLState class value
 is '<i>40</i>', or under vendor-specified conditions.</div>
</td>
</tr>
<tr class="altColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLTransientConnectionException.html" title="class in java.sql">SQLTransientConnectionException</a></td>
<td class="colLast">
<div class="block">The subclass of <a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLException.html" title="class in java.sql"><code>SQLException</code></a> for the SQLState class
 value '<i>08</i>', or under vendor-specified conditions.</div>
</td>
</tr>
<tr class="rowColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLTransientException.html" title="class in java.sql">SQLTransientException</a></td>
<td class="colLast">
<div class="block">The subclass of <a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLException.html" title="class in java.sql"><code>SQLException</code></a> is thrown in situations where a
 previously failed operation might be able to succeed when the operation is
 retried without any intervention by application-level functionality.</div>
</td>
</tr>
<tr class="altColor">
<td class="colFirst"><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/SQLWarning.html" title="class in java.sql">SQLWarning</a></td>
<td class="colLast">
<div class="block">An exception that provides information on  database access
 warnings.</div>
</td>
</tr>
</tbody>
</table>
</li>
</ul>
<a name="package.description">
<!--   -->
</a>
<h2 title="Package java.sql Description">Package java.sql Description</h2>
<div class="block">Provides the API for accessing and processing data stored in a 
data source (usually a relational database) using the 
Java<sup><font size="-2">TM</font></sup> programming language. 
This API includes a framework whereby different
drivers can be installed dynamically to access different data sources.
Although the JDBC<sup><font size="-2">TM</font></sup> API is mainly geared 
to passing SQL statements to a database, it provides for reading and
writing data from any data source with a tabular format.
The reader/writer facility, available through the 
<code>javax.sql.RowSet</code> group of interfaces, can be customized to
use and update data from a spread sheet, flat file, or any other tabular 
data source.
<p>
</p><h2>What the JDBC<sup><font size="-2">TM</font></sup> 4.2 API Includes</h2>
The JDBC<sup><font size="-2">TM</font></sup> 4.2 API includes both
the <code>java.sql</code> package, referred to as the JDBC core API,
and the <code>javax.sql</code> package, referred to as the JDBC Optional
Package API. This complete JDBC API
is included in the Java<sup><font size="-2">TM</font></sup>  
Standard Edition (Java SE<sup><font size="-2">TM</font></sup>), version 7.
The <code>javax.sql</code> package extends the functionality of the JDBC API 
from a client-side API to a server-side API, and it is an essential part
of the Java<sup><font size="-2">TM</font></sup>  Enterprise Edition
(Java EE<sup><font size="-2">TM</font></sup>) technology. 
<p>
</p><h2>Versions</h2>
The JDBC 4.2 API incorporates all of the previous JDBC API versions:
<ul>
    <li> The JDBC 4.1 API</li>
    <li> The JDBC 4.0 API</li>
    <li> The JDBC 3.0 API</li>
    <li> The JDBC 2.1 core API</li>
 <li> The JDBC 2.0 Optional Package API<br>
      (Note that the JDBC 2.1 core API and the JDBC 2.0 Optional Package
      API together are referred to as the JDBC 2.0 API.)</li>
 <li> The JDBC 1.2 API</li>
 <li> The JDBC 1.0 API</li>
</ul>
<p>
Classes, interfaces, methods, fields, constructors, and exceptions 
have the following "since" tags that indicate when they were introduced 
into the Java platform. When these "since" tags are used in
Javadoc<sup><font size="-2">TM</font></sup> comments for the JDBC API,
they indicate the following:
</p><ul>
    <li>Since 1.8 -- new in the JDBC 4.2 API and part of the Java SE platform,
        version 8</li>
 <li>Since 1.7 -- new in the JDBC 4.1 API and part of the Java SE platform,
     version 7</li>
<li>Since 1.6 -- new in the JDBC 4.0 API and part of the Java SE platform,
    version 6</li>
 <li>Since 1.4 -- new in the JDBC 3.0 API and part of the J2SE platform, 
     version 1.4</li>
 <li>Since 1.2 -- new in the JDBC 2.0 API and part of the J2SE platform, 
     version 1.2</li>
 <li>Since 1.1 or no "since" tag -- in the original JDBC 1.0 API and part of
     the JDK<sup><font size="-2">TM</font></sup>, version 1.1</li>
</ul>
<p>
<b>NOTE:</b> Many of the new features are optional; consequently, there is 
some variation in drivers and the features they support. Always 
check your driver's documentation to see whether it supports a feature before
you try to use it.
</p><p>
<b>NOTE:</b> The class <code>SQLPermission</code> was added in the
Java<sup><font size="-2">TM</font></sup> 2 SDK, Standard Edition, 
version 1.3 release. This class is used to prevent unauthorized
access to the logging stream associated with the <code>DriverManager</code>,
which may contain information such as table names, column data, and so on.
</p><p>

</p><h2>What the <code>java.sql</code> Package Contains</h2>
The <code>java.sql</code> package contains API for the following:
<ul>
  <li>Making a connection with a database via the <code>DriverManager</code> facility
  <ul>
         <li><code>DriverManager</code> class -- makes a connection with a driver
         </li><li><code>SQLPermission</code> class -- provides permission when code
                  running within a Security Manager, such as an applet,
                  attempts to set up a logging stream through the
                  <code>DriverManager</code>
         </li><li><code>Driver</code> interface -- provides the API for registering
             and connecting drivers based on JDBC technology ("JDBC drivers"); 
             generally used only by the <code>DriverManager</code> class
         </li><li><code>DriverPropertyInfo</code> class -- provides properties for a
             JDBC driver; not used by the general user
  </li></ul>
  </li><li>Sending SQL statements to a database
  <ul>
         <li><code>Statement</code> --  used to send basic SQL statements
         </li><li><code>PreparedStatement</code> --  used to send prepared statements or 
              basic SQL statements (derived from <code>Statement</code>)
         </li><li><code>CallableStatement</code> --  used to call database stored 
              procedures (derived from <code>PreparedStatement</code>)
         </li><li><code>Connection</code> interface --  provides methods for creating
             statements and managing connections and their properties
         </li><li><code>Savepoint</code> --  provides savepoints in a transaction

  </li></ul>
  </li><li>Retrieving and updating the results of a query
  <ul>
         <li><code>ResultSet</code> interface
  </li></ul>
  </li><li>Standard mappings for SQL types to classes and interfaces in the 
      Java programming language
  <ul>
         <li><code>Array</code> interface -- mapping for SQL <code>ARRAY</code> 
         </li><li><code>Blob</code> interface -- mapping for SQL <code>BLOB</code> 
         </li><li><code>Clob</code> interface -- mapping for SQL <code>CLOB</code>
         </li><li><code>Date</code> class -- mapping for SQL <code>DATE</code> 
          </li><li><code>NClob</code> interface -- mapping for SQL <code>NCLOB</code>
         </li><li><code>Ref</code> interface -- mapping for SQL <code>REF</code> 
          </li><li><code>RowId</code> interface -- mapping for SQL <code>ROWID</code>
         </li><li><code>Struct</code> interface -- mapping for SQL <code>STRUCT</code> 
          </li><li><code>SQLXML</code> interface -- mapping for SQL <code>XML</code>
         </li><li><code>Time</code> class -- mapping for SQL <code>TIME</code> 
         </li><li><code>Timestamp</code> class -- mapping for SQL <code>TIMESTAMP</code> 
         </li><li><code>Types</code> class -- provides constants for SQL types
  </li></ul>
  </li><li>Custom mapping an SQL user-defined type (UDT) to a class in the
          Java programming language
  <ul>
         <li><code>SQLData</code> interface -- specifies the mapping of
              a UDT to an instance of this class
         </li><li><code>SQLInput</code> interface -- provides methods for reading
              UDT attributes from a stream
         </li><li><code>SQLOutput</code> interface -- provides methods for writing
              UDT attributes back to a stream
  </li></ul>
  </li><li>Metadata
  <ul>
         <li><code>DatabaseMetaData</code> interface -- provides information
              about the database
         </li><li><code>ResultSetMetaData</code> interface -- provides information
              about the columns of a <code>ResultSet</code> object
         </li><li><code>ParameterMetaData</code> interface -- provides information
              about the parameters to <code>PreparedStatement</code> commands
  </li></ul>
  </li><li>Exceptions
        <ul>
          <li><code>SQLException</code> -- thrown by most methods when there
                 is a problem accessing data and by some methods for other reasons
          </li><li><code>SQLWarning</code> -- thrown to indicate a warning
          </li><li><code>DataTruncation</code> -- thrown to indicate that data may have
          been truncated
          </li><li><code>BatchUpdateException</code> -- thrown to indicate that not all
                 commands in a batch update executed successfully
        </li></ul>
</li></ul>
<p>
    </p><h3><code>java.sql</code> and <code>javax.sql</code> Features Introduced in the JDBC 4.2 API</h3>
<ul>
    <li>Added <code>JDBCType</code>  enum and <code>SQLType</code> interface</li>
    <li>Support for <code>REF CURSORS</code> in <code>CallableStatement</code> 
    </li>
    <li><code>DatabaseMetaData</code> methods to return maximum Logical LOB size
        and if Ref Cursors are supported</li>
    <li>Added support for large update counts</li>

</ul>
<p>
    </p><h3><code>java.sql</code> and <code>javax.sql</code> Features Introduced in the JDBC 4.1 API</h3>
<ul>
    <li>Allow <code>Connection</code>,
        <code>ResultSet</code> and <code>Statement</code> objects to be
        used with the try-with-resources statement</li>
    <li>Supported added to <code>CallableStatement</code> and
        <code>ResultSet</code> to specify the Java type to convert to via the
        <code>getObject</code> method</li>
    <li><code>DatabaseMetaData</code> methods to return PseudoColumns and if a
        generated key is always returned</li>
    <li>Added support to <code>Connection</code> to specify a database schema,
    abort and timeout a physical connection.</li>
    <li>Added support to close a <code>Statement</code> object when its dependent
    objects have been closed</li>
    <li>Support for obtaining the parent logger for a <code>Driver</code>,
     <code>DataSource</code>, <code>ConnectionPoolDataSource</code> and
     <code>XADataSource</code></li>

</ul>
<h3><code>java.sql</code> and <code>javax.sql</code> Features Introduced in the JDBC 4.0 API</h3>
<ul>
  <li>auto java.sql.Driver discovery -- no longer need to load a 
<code>java.sql.Driver</code> class via <code>Class.forName</code>
 </li><li>National Character Set support added
 </li><li>Support added for the SQL:2003 XML data type
 </li><li>SQLException enhancements -- Added support for cause chaining; New SQLExceptions
 added for common SQLState class value codes
 </li><li>Enhanced Blob/Clob functionality -- Support provided to create and free a Blob/Clob instance
 as well as additional methods added to improve accessibility
 </li><li>Support added for accessing a SQL ROWID
 </li><li>Support added to allow a JDBC application to access an instance of a JDBC resource
 that has been wrapped by a vendor, usually in an application server or connection 
 pooling environment.
 </li><li>Availability to be notified when a <code>PreparedStatement</code> that is associated
 with a <code>PooledConnection</code> has been closed or the driver determines is invalid
 
 
</li></ul>
<p>
</p><p>
</p><h3><code>java.sql</code> and <code>javax.sql</code> Features Introduced in the JDBC 3.0 API</h3>
<ul>
  <li>Pooled statements -- reuse of statements associated with a pooled 
       connection
  </li><li>Savepoints -- allow a transaction to be rolled back to a designated
      savepoint
  </li><li>Properties defined for <code>ConnectionPoolDataSource</code> -- specify
      how connections are to be pooled
  </li><li>Metadata for parameters of a <code>PreparedStatement</code> object
  </li><li>Ability to retrieve values from automatically generated columns
  </li><li>Ability to have multiple <code>ResultSet</code> objects 
       returned from <code>CallableStatement</code> objects open at the
      same time
  </li><li>Ability to identify parameters to <code>CallableStatement</code>
      objects by name as well as by index
  </li><li><code>ResultSet</code> holdability -- ability to specify whether cursors
      should be held open or closed at the end of a transaction
  </li><li>Ability to retrieve and update the SQL structured type instance that a
      <code>Ref</code> object references
  </li><li>Ability to programmatically update <code>BLOB</code>,
      <code>CLOB</code>, <code>ARRAY</code>, and <code>REF</code> values.
  </li><li>Addition of the <code>java.sql.Types.DATALINK</code> data type -- 
      allows JDBC drivers access to objects stored outside a data source
  </li><li>Addition of metadata for retrieving SQL type hierarchies
</li></ul>
<p>
</p><h3><code>java.sql</code> Features Introduced in the JDBC 2.1 Core API</h3>
<ul>
  <li>Scrollable result sets--using new methods in the <code>ResultSet</code>
          interface that allow the cursor to be moved to a particular row or to a
          position relative to its current position
  </li><li>Batch updates
  </li><li>Programmatic updates--using <code>ResultSet</code> updater methods
  </li><li>New data types--interfaces mapping the SQL3 data types
  </li><li>Custom mapping of user-defined types (UDTs)
  </li><li>Miscellaneous features, including performance hints, the use of character
          streams, full precision for <code>java.math.BigDecimal</code> values,
          additional security, and
          support for time zones in date, time, and timestamp values. 
</li></ul>
<p>
</p><h3><code>javax.sql</code> Features Introduced in the JDBC 2.0 Optional
Package API</h3>
<ul>
  <li>The <code>DataSource</code> interface as a means of making a connection.  The
      Java Naming and Directory Interface<sup><font size="-2">TM</font></sup>
      (JNDI) is used for registering a <code>DataSource</code> object with a 
      naming service and also for  retrieving it.
  </li><li>Pooled connections -- allowing connections to be used and reused
  </li><li>Distributed transactions -- allowing a transaction to span diverse
      DBMS servers
  </li><li><code>RowSet</code> technology -- providing a convenient means of
       handling and passing data
</li></ul>
<p>
</p><p>
</p><h3>Custom Mapping of UDTs</h3>
A user-defined type (UDT) defined in SQL can be mapped to a class in the Java
programming language. An SQL structured type or an SQL <code>DISTINCT</code>
type are the UDTs that may be custom mapped.  The following three
steps set up a custom mapping:
<ol>
  <li>Defining the SQL structured type or <code>DISTINCT</code> type in SQL
  </li><li>Defining the class in the Java programming language to which the
          SQL UDT will be mapped.  This class must implement the
          <code>SQLData</code> interface.
  </li><li>Making an entry in a <code>Connection</code> object's type map
      that contains two things:
   <ul>
       <li>the fully-qualified SQL name of the UDT
       </li><li>the <code>Class</code> object for the class that implements the 
           <code>SQLData</code> interface
   </li></ul>
</li></ol>
<p>
When these are in place for a UDT, calling the methods
<code>ResultSet.getObject</code> or <code>CallableStatement.getObject</code> 
on that UDT will automatically retrieve the custom mapping for it. Also, the
<code>PreparedStatement.setObject</code> method will automatically map the
object back to its SQL type to store it in the data source.

</p><h2>Package Specification</h2>

<ul>
  <li><a href="http://java.sun.com/products/jdbc/download.html">Specification 
      of the JDBC 4.0 API</a>
</li></ul>

<h2>Related Documentation</h2>

<ul>
  <li><a href="https://docs.oracle.com/javase/8/docs/technotes/guides/jdbc/getstart/GettingStartedTOC.fm.html">Getting Started</a>--overviews of the major interfaces
<p>
  </p></li><li><a href="http://java.sun.com/docs/books/tutorial/jdbc">Chapters on the JDBC 
     API</a>--from the online version of <i>The Java Tutorial Continued</i>
<p>
  </p></li><li><a href="http://java.sun.com/docs/books/jdbc">
<i>JDBC<sup><font size="-2">TM</font></sup>API Tutorial and Reference, 
Third Edition</i></a>--
a complete reference and tutorial for the JDBC 3.0 API
</li></ul>
<p></p></div>
<dl>
<dt><span class="simpleTagLabel">Since:</span></dt>
<dd>1.1</dd>
</dl>
</div>
<!-- ======= START OF BOTTOM NAVBAR ====== -->
<div class="bottomNav"><a name="navbar.bottom">
<!--   -->
</a>
<div class="skipNav"><a href="#skip.navbar.bottom" title="Skip navigation links">Skip navigation links</a></div>
<a name="navbar.bottom.firstrow">
<!--   -->
</a>
<ul class="navList" title="Navigation">
<li><a href="https://docs.oracle.com/javase/8/docs/api/overview-summary.html">Overview</a></li>
<li class="navBarCell1Rev">Package</li>
<li>Class</li>
<li><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/package-use.html">Use</a></li>
<li><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/package-tree.html">Tree</a></li>
<li><a href="https://docs.oracle.com/javase/8/docs/api/deprecated-list.html">Deprecated</a></li>
<li><a href="https://docs.oracle.com/javase/8/docs/api/index-files/index-1.html">Index</a></li>
<li><a href="https://docs.oracle.com/javase/8/docs/api/help-doc.html">Help</a></li>
</ul>
<div class="aboutLanguage"><strong>Java�&nbsp;Platform<br>Standard&nbsp;Ed.&nbsp;8</strong></div>
</div>
<div class="subNav">
<ul class="navList">
<li><a href="https://docs.oracle.com/javase/8/docs/api/java/security/spec/package-summary.html">Prev&nbsp;Package</a></li>
<li><a href="https://docs.oracle.com/javase/8/docs/api/java/text/package-summary.html">Next&nbsp;Package</a></li>
</ul>
<ul class="navList">
<li><a href="https://docs.oracle.com/javase/8/docs/api/index.html?java/sql/package-summary.html" target="_top">Frames</a></li>
<li><a href="https://docs.oracle.com/javase/8/docs/api/java/sql/package-summary.html" target="_top">No&nbsp;Frames</a></li>
</ul>
<ul class="navList" id="allclasses_navbar_bottom" style="display: block;">
<li><a href="https://docs.oracle.com/javase/8/docs/api/allclasses-noframe.html">All&nbsp;Classes</a></li>
</ul>
<div>
<script type="text/javascript">
  allClassesLink = document.getElementById("allclasses_navbar_bottom");
  if(window==top) {
    allClassesLink.style.display = "block";
  }
  else {
    allClassesLink.style.display = "none";
  }
  
</script>
</div>
<a name="skip.navbar.bottom">
<!--   -->
</a></div>
<!-- ======== END OF BOTTOM NAVBAR ======= -->
<p class="legalCopy"><small><font size="-1"> <a href="http://bugreport.sun.com/bugreport/">Submit a bug or feature</a> <br>For further API reference and developer documentation, see <a href="https://docs.oracle.com/javase/8/docs/index.html" target="_blank">Java SE Documentation</a>.
 That documentation contains more detailed, developer-targeted 
descriptions, with conceptual overviews, definitions of terms, 
workarounds, and working code examples.<br> <a href="https://docs.oracle.com/javase/8/docs/legal/cpyr.html">Copyright</a> � 1993, 2024, Oracle and/or its affiliates.  All rights reserved. Use is subject to <a href="http://download.oracle.com/otndocs/jcp/java_se-8-mrel-spec/license.html">license terms</a>. Also see the <a target="_blank" href="http://www.oracle.com/technetwork/java/redist-137594.html">documentation redistribution policy</a>. <span>Modify <a id="teconsent" href="#" consent="undefined" aria-label="Open Cookie Preferences Modal" class="truste_caIcon_display" role="complementary"><script async="async" type="text/javascript" crossorigin="" importance="high" src="README_files/v1.7-4958"></script><a role="link" id="icon-id04788456727994995" tabindex="0" lang="en" aria-haspopup="dialog" aria-label="Cookie Preferences, opens a dedicated popup modal window" class="truste_cursor_pointer">Cookie Preferences</a></a>. Modify <a id="adchoices" target="_blank" href="https://www.oracle.com/legal/privacy/marketing-cloud-data-cloud-privacy-policy.html#12">Ad Choices</a>.</span></font></small></p>
<!-- Start SiteCatalyst code   -->
<script type="application/javascript" src="README_files/ora_docs.js"></script><script src="README_files/ora_code_docs.js"></script><script src="README_files/ora_code.js"></script>
<!-- End SiteCatalyst code -->
<noscript>
<p>Scripting on this page tracks web page traffic, but does not change the content in any way.</p>
</noscript>


<script type="text/javascript" src="README_files/notice.es" id="truste_0.34182802040383653"></script><iframe style="display: none;" name="trustarc_notice" id="trustarcNoticeFrame" title="Trustarc Cross-Domain Consent Frame" src="README_files/get.html"></iframe></body></html>
