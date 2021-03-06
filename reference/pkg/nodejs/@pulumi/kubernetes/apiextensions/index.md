---
title: Module apiextensions
---

<!-- WARNING: this page was generated by a tool. Do not edit it by hand. -->
<!-- To change it, please see https://github.com/pulumi/docs/tree/master/tools/tscdocgen. -->

<a href="../index.html">@pulumi/kubernetes</a> &gt; apiextensions

<div class="toggleVisible" markdown="1">
<div class="collapsed" markdown="1">
<h2 class="pdoc-module-header toggleButton" title="Click to show Index">Index ▹</h2>
</div>
<div class="expanded" markdown="1">
<h2 class="pdoc-module-header toggleButton" title="Click to hide Index">Index ▾</h2>
<div class="pdoc-module-contents" markdown="1">
* <a href="#CustomResource">class CustomResource</a>
* <a href="#CustomResourceArgs">interface CustomResourceArgs</a>
* <a href="#CustomResourceGetOptions">interface CustomResourceGetOptions</a>

<a href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/apiextensions/CustomResource.ts">apiextensions/CustomResource.ts</a> 
</div>
</div>
</div>

<div class="toggleVisible" markdown="1">
<div class="collapsed" markdown="1">
<h2 class="pdoc-module-header toggleButton" title="Click to show Modules">Modules ▹</h2>
</div>
<div class="expanded" markdown="1">
<h2 class="pdoc-module-header toggleButton" title="Click to hide Modules">Modules ▾</h2>
<div class="pdoc-module-contents" markdown="1">
* <a href="v1beta1">apiextensions/v1beta1</a>
</div>
</div>
</div>

<h2 class="pdoc-module-header" id="CustomResource">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/apiextensions/CustomResource.ts#L84">class <b>CustomResource</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">
<pre class="highlight"><span class='kd'>extends</span> <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#CustomResource'>CustomResource</a></pre>

CustomResource represents an instance of a CustomResourceDefinition (CRD). For example, the
CoreOS Prometheus operator exposes a CRD `monitoring.coreos.com/ServiceMonitor`; to
instantiate this as a Pulumi resource, one could call `new CustomResource`, passing the
`ServiceMonitor` resource definition as an argument.

<h3 class="pdoc-member-header" id="CustomResource-constructor">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/apiextensions/CustomResource.ts#L126"> <b>constructor</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">

<pre class="highlight"><span class='kd'></span><span class='kd'>new</span> CustomResource(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, args: <a href='#CustomResourceArgs'>CustomResourceArgs</a>, opts?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#CustomResourceOptions'>pulumi.CustomResourceOptions</a>)</pre>


Create a CustomResource resource with the given unique name, arguments, and options.

* `name` The _unique_ name of the resource.
* `args` The arguments to use to populate this resource&#39;s properties.
* `opts` A bag of options that control this resource&#39;s behavior.

</div>
<h3 class="pdoc-member-header" id="CustomResource-get">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/apiextensions/CustomResource.ts#L117">method <b>get</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">

<pre class="highlight"><span class='kd'>public static </span>get(name: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>, opts: <a href='#CustomResourceGetOptions'>CustomResourceGetOptions</a>): <a href='#CustomResource'>CustomResource</a></pre>


Get the state of an existing `CustomResource`, as identified by `id`.
Typically this ID  is of the form <namespace>/<name>; if <namespace> is omitted, then (per
Kubernetes convention) the ID becomes default/<name>.

Pulumi will keep track of this resource using `name` as the Pulumi ID.

</div>
<h3 class="pdoc-member-header" id="CustomResource-getInputs">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/apiextensions/CustomResource.ts#L125">method <b>getInputs</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">

<pre class="highlight"><span class='kd'>public </span>getInputs(): <a href='#CustomResourceArgs'>CustomResourceArgs</a></pre>

</div>
<h3 class="pdoc-member-header" id="CustomResource-getProvider">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L14">method <b>getProvider</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">

<pre class="highlight"><span class='kd'></span>getProvider(moduleMember: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>): ProviderResource | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span></pre>

</div>
<h3 class="pdoc-member-header" id="CustomResource-isInstance">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L101">method <b>isInstance</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">

<pre class="highlight"><span class='kd'>static </span>isInstance(obj: <span class='kd'><a href='https://www.typescriptlang.org/docs/handbook/basic-types.html#any'>any</a></span>): <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Boolean'>boolean</a></span></pre>


Returns true if the given object is an instance of CustomResource.  This is designed to work even when
multiple copies of the Pulumi SDK have been loaded into the same process.

</div>
<h3 class="pdoc-member-header" id="CustomResource-apiVersion">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/apiextensions/CustomResource.ts#L91">property <b>apiVersion</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'>public </span>apiVersion: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

APIVersion defines the versioned schema of this representation of an object. Servers should
convert recognized schemas to the latest internal value, and may reject unrecognized
values. More info:
https://git.k8s.io/community/contributors/devel/api-conventions.md#resources

</div>
<h3 class="pdoc-member-header" id="CustomResource-id">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L96">property <b>id</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>id: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>Output</a>&lt;<a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#ID'>ID</a>&gt;;</pre>

id is the provider-assigned unique ID for this managed resource.  It is set during
deployments and may be missing (undefined) during planning phases.

</div>
<h3 class="pdoc-member-header" id="CustomResource-kind">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/apiextensions/CustomResource.ts#L99">property <b>kind</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'>public </span>kind: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>pulumi.Output</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

Kind is a string value representing the REST resource this object represents. Servers may
infer this from the endpoint the client submits requests to. Cannot be updated. In
CamelCase. More info:
https://git.k8s.io/community/contributors/devel/api-conventions.md#types-kinds

</div>
<h3 class="pdoc-member-header" id="CustomResource-metadata">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/apiextensions/CustomResource.ts#L105">property <b>metadata</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'>public </span>metadata: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>pulumi.Output</a>&lt;outputApi.meta.v1.ObjectMeta&gt;;</pre>

Standard object metadata; More info:
https://git.k8s.io/community/contributors/devel/api-conventions.md#metadata.

</div>
<h3 class="pdoc-member-header" id="CustomResource-urn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L12">property <b>urn</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>urn: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Output'>Output</a>&lt;<a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#URN'>URN</a>&gt;;</pre>

urn is the stable logical URN used to distinctly address a resource, both before and after
deployments.

</div>
</div>
<h2 class="pdoc-module-header" id="CustomResourceArgs">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/apiextensions/CustomResource.ts#L29">interface <b>CustomResourceArgs</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">

CustomResourceArgs represents a resource definition we'd use to create an instance of a
Kubernetes CustomResourceDefinition (CRD). For example, the CoreOS Prometheus operator
exposes a CRD `monitoring.coreos.com/ServiceMonitor`; to create a `ServiceMonitor`, we'd
pass a `CustomResourceArgs` containing the `ServiceMonitor` definition to
`apiextensions.CustomResource`.

NOTE: This type is fairly loose, since other than `apiVersion` and `kind`, there are no
fields required across all CRDs.

<h3 class="pdoc-member-header" id="CustomResourceArgs-apiVersion">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/apiextensions/CustomResource.ts#L36">property <b>apiVersion</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>apiVersion: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

APIVersion defines the versioned schema of this representation of an object. Servers should
convert recognized schemas to the latest internal value, and may reject unrecognized
values. More info:
https://git.k8s.io/community/contributors/devel/api-conventions.md#resources

</div>
<h3 class="pdoc-member-header" id="CustomResourceArgs-kind">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/apiextensions/CustomResource.ts#L44">property <b>kind</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>kind: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

Kind is a string value representing the REST resource this object represents. Servers may
infer this from the endpoint the client submits requests to. Cannot be updated. In
CamelCase. More info:
https://git.k8s.io/community/contributors/devel/api-conventions.md#types-kinds

</div>
<h3 class="pdoc-member-header" id="CustomResourceArgs-metadata">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/apiextensions/CustomResource.ts#L50">property <b>metadata</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>metadata?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;inputApi.meta.v1.ObjectMeta&gt;;</pre>

Standard object metadata; More info:
https://git.k8s.io/community/contributors/devel/api-conventions.md#metadata.

</div>
</div>
<h2 class="pdoc-module-header" id="CustomResourceGetOptions">
<a class="pdoc-member-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/apiextensions/CustomResource.ts#L58">interface <b>CustomResourceGetOptions</b></a>
</h2>
<div class="pdoc-module-contents" markdown="1">
<pre class="highlight"><span class='kd'>extends</span> <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#CustomResourceOptions'>CustomResourceOptions</a></pre>

CustomResourceGetOptions uniquely identifies a Kubernetes CustomResource, primarily for use
in supplied to `apiextensions.CustomResource#get`.

<h3 class="pdoc-member-header" id="CustomResourceGetOptions-apiVersion">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/apiextensions/CustomResource.ts#L63">property <b>apiVersion</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>apiVersion: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

apiVersion is the API version of the apiExtensions.CustomResource we wish to select,
as specified by the CustomResourceDefinition that defines it on the API server.

</div>
<h3 class="pdoc-member-header" id="CustomResourceGetOptions-deleteBeforeReplace">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L74">property <b>deleteBeforeReplace</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>deleteBeforeReplace?: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> | <span class='kd'>false</span> | <span class='kd'>true</span>;</pre>

When set to true, deleteBeforeReplace indicates that this resource should be deleted before its replacement
is created when replacement is necessary.

</div>
<h3 class="pdoc-member-header" id="CustomResourceGetOptions-dependsOn">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L44">property <b>dependsOn</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>dependsOn?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>Input</a>&lt;<a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>Input</a>&lt;<a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Resource'>Resource</a>&gt;[]&gt; | <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>Input</a>&lt;<a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Resource'>Resource</a>&gt;;</pre>

An optional additional explicit dependencies on other resources.

</div>
<h3 class="pdoc-member-header" id="CustomResourceGetOptions-id">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/apiextensions/CustomResource.ts#L75">property <b>id</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>id: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#ID'>pulumi.ID</a>&gt;;</pre>

An ID for the Kubernetes resource to retrive. Takes the form <namespace>/<name> or
<name>.

</div>
<h3 class="pdoc-member-header" id="CustomResourceGetOptions-ignoreChanges">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L52">property <b>ignoreChanges</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>ignoreChanges?: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>[];</pre>

Ignore changes to any of the specified properties.

</div>
<h3 class="pdoc-member-header" id="CustomResourceGetOptions-kind">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/apiextensions/CustomResource.ts#L69">property <b>kind</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>kind: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Input'>pulumi.Input</a>&lt;<span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>&gt;;</pre>

kind is the kind of the apiextensions.CustomResource we wish to select, as specified by
the CustomResourceDefinition that defines it on the API server.

</div>
<h3 class="pdoc-member-header" id="CustomResourceGetOptions-parent">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L40">property <b>parent</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>parent?: <a href='https://pulumi.io/reference/pkg/nodejs/@pulumi/pulumi/#Resource'>Resource</a>;</pre>

An optional parent resource to which this resource belongs.

</div>
<h3 class="pdoc-member-header" id="CustomResourceGetOptions-protect">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L48">property <b>protect</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>protect?: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> | <span class='kd'>false</span> | <span class='kd'>true</span>;</pre>

When set to true, protect ensures this resource cannot be deleted.

</div>
<h3 class="pdoc-member-header" id="CustomResourceGetOptions-provider">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L69">property <b>provider</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>provider?: ProviderResource;</pre>

An optional provider to use for this resource's CRUD operations. If no provider is supplied, the default
provider for the resource's package will be used. The default provider is pulled from the parent's
provider bag (see also ComponentResourceOptions.providers).

</div>
<h3 class="pdoc-member-header" id="CustomResourceGetOptions-version">
<a class="pdoc-child-name" href="https://github.com/pulumi/pulumi-kubernetes/blob/master/sdk/nodejs/node_modules/@pulumi/pulumi/resource.d.ts#L58">property <b>version</b></a>
</h3>
<div class="pdoc-member-contents" markdown="1">
<pre class="highlight"><span class='kd'></span>version?: <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/undefined'>undefined</a></span> | <span class='kd'><a href='https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String'>string</a></span>;</pre>

An optional version, corresponding to the version of the provider plugin that should be used when operating on
this resource. This version overrides the version information inferred from the current package and should
rarely be used.

</div>
</div>
