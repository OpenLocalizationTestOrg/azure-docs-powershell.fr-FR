# <a name="table-of-contents"></a><span data-ttu-id="3c01a-101">Sommaire</span><span class="sxs-lookup"><span data-stu-id="3c01a-101">Table of Contents</span></span>
1. [<span data-ttu-id="3c01a-102">Suppression des paramètres Force</span><span class="sxs-lookup"><span data-stu-id="3c01a-102">Removal of Force parameters</span></span>](#removal-of-force-parameters)
2. [<span data-ttu-id="3c01a-103">Modification des paramètres Tag</span><span class="sxs-lookup"><span data-stu-id="3c01a-103">Change of Tag parameters</span></span>](#change-of-tag-parameters)
3. [<span data-ttu-id="3c01a-104">Dernières modifications des applets de commande Storage</span><span class="sxs-lookup"><span data-stu-id="3c01a-104">Breaking changes to Storage cmdlets</span></span>](#breaking-changes-to-storage-cmdlets)
4. [<span data-ttu-id="3c01a-105">Dernières modifications des applets de commande AD</span><span class="sxs-lookup"><span data-stu-id="3c01a-105">Breaking changes to AD cmdlets</span></span>](#breaking-changes-to-ad-cmdlets)

## <a name="removal-of-force-parameters"></a><span data-ttu-id="3c01a-106">Suppression des paramètres Force</span><span class="sxs-lookup"><span data-stu-id="3c01a-106">Removal of Force parameters</span></span>

<span data-ttu-id="3c01a-107">Dans cette version, nous avons supprimé l’ensemble des paramètres `Force` obsolètes des applets de commande et les avertissements correspondants signalant la suppression du paramètre dans une version ultérieure.</span><span class="sxs-lookup"><span data-stu-id="3c01a-107">This release, we removed all Obsolete `Force` parameters from cmdlets and the corresponding warnings that the parameter would be removed in a future release.</span></span>

<span data-ttu-id="3c01a-108">Les applets de commande suivantes sont affectées par cette modification :</span><span class="sxs-lookup"><span data-stu-id="3c01a-108">The following cmdlets are affected by this change:</span></span>

<span data-ttu-id="3c01a-109">**ApiManagement**</span><span class="sxs-lookup"><span data-stu-id="3c01a-109">**ApiManagement**</span></span>
- <span data-ttu-id="3c01a-110">Remove-AzureRmApiManagement</span><span class="sxs-lookup"><span data-stu-id="3c01a-110">Remove-AzureRmApiManagement</span></span>
- <span data-ttu-id="3c01a-111">Remove-AzureRmApiManagementApi</span><span class="sxs-lookup"><span data-stu-id="3c01a-111">Remove-AzureRmApiManagementApi</span></span>
- <span data-ttu-id="3c01a-112">Remove-AzureRmApiManagementGroup</span><span class="sxs-lookup"><span data-stu-id="3c01a-112">Remove-AzureRmApiManagementGroup</span></span>
- <span data-ttu-id="3c01a-113">Remove-AzureRmApiManagementLogger</span><span class="sxs-lookup"><span data-stu-id="3c01a-113">Remove-AzureRmApiManagementLogger</span></span>
- <span data-ttu-id="3c01a-114">Remove-AzureRmApiManagementOpenIdConnectProvider</span><span class="sxs-lookup"><span data-stu-id="3c01a-114">Remove-AzureRmApiManagementOpenIdConnectProvider</span></span>
- <span data-ttu-id="3c01a-115">Remove-AzureRmApiManagementOperation</span><span class="sxs-lookup"><span data-stu-id="3c01a-115">Remove-AzureRmApiManagementOperation</span></span>
- <span data-ttu-id="3c01a-116">Remove-AzureRmApiManagementPolicy</span><span class="sxs-lookup"><span data-stu-id="3c01a-116">Remove-AzureRmApiManagementPolicy</span></span>
- <span data-ttu-id="3c01a-117">Remove-AzureRmApiManagementProduct</span><span class="sxs-lookup"><span data-stu-id="3c01a-117">Remove-AzureRmApiManagementProduct</span></span>
- <span data-ttu-id="3c01a-118">Remove-AzureRmApiManagementProperty</span><span class="sxs-lookup"><span data-stu-id="3c01a-118">Remove-AzureRmApiManagementProperty</span></span>
- <span data-ttu-id="3c01a-119">Remove-AzureRmApiManagementSubscription</span><span class="sxs-lookup"><span data-stu-id="3c01a-119">Remove-AzureRmApiManagementSubscription</span></span>
- <span data-ttu-id="3c01a-120">Remove-AzureRmApiManagementUser</span><span class="sxs-lookup"><span data-stu-id="3c01a-120">Remove-AzureRmApiManagementUser</span></span>

<span data-ttu-id="3c01a-121">**Automation**</span><span class="sxs-lookup"><span data-stu-id="3c01a-121">**Automation**</span></span>
- <span data-ttu-id="3c01a-122">Remove-AzureRmAutomationCertificate</span><span class="sxs-lookup"><span data-stu-id="3c01a-122">Remove-AzureRmAutomationCertificate</span></span>
- <span data-ttu-id="3c01a-123">Remove-AzureRmAutomationCredential</span><span class="sxs-lookup"><span data-stu-id="3c01a-123">Remove-AzureRmAutomationCredential</span></span>
- <span data-ttu-id="3c01a-124">Remove-AzureRmAutomationVariable</span><span class="sxs-lookup"><span data-stu-id="3c01a-124">Remove-AzureRmAutomationVariable</span></span>
- <span data-ttu-id="3c01a-125">Remove-AzureRmAutomationWebhook</span><span class="sxs-lookup"><span data-stu-id="3c01a-125">Remove-AzureRmAutomationWebhook</span></span>

<span data-ttu-id="3c01a-126">**Batch**</span><span class="sxs-lookup"><span data-stu-id="3c01a-126">**Batch**</span></span>
- <span data-ttu-id="3c01a-127">Remove-AzureBatchCertificate</span><span class="sxs-lookup"><span data-stu-id="3c01a-127">Remove-AzureBatchCertificate</span></span>
- <span data-ttu-id="3c01a-128">Remove-AzureBatchComputeNode</span><span class="sxs-lookup"><span data-stu-id="3c01a-128">Remove-AzureBatchComputeNode</span></span>
- <span data-ttu-id="3c01a-129">Remove-AzureBatchComputeNodeUser</span><span class="sxs-lookup"><span data-stu-id="3c01a-129">Remove-AzureBatchComputeNodeUser</span></span>

<span data-ttu-id="3c01a-130">**DataFactories**</span><span class="sxs-lookup"><span data-stu-id="3c01a-130">**DataFactories**</span></span>
- <span data-ttu-id="3c01a-131">Resume-AzureRmDataFactoryPipeline</span><span class="sxs-lookup"><span data-stu-id="3c01a-131">Resume-AzureRmDataFactoryPipeline</span></span>
- <span data-ttu-id="3c01a-132">Set-AzureRmDataFactoryPipelineActivePeriod</span><span class="sxs-lookup"><span data-stu-id="3c01a-132">Set-AzureRmDataFactoryPipelineActivePeriod</span></span>
- <span data-ttu-id="3c01a-133">Suspend-AzureRmDataFactoryPipeline</span><span class="sxs-lookup"><span data-stu-id="3c01a-133">Suspend-AzureRmDataFactoryPipeline</span></span>

<span data-ttu-id="3c01a-134">**DataLakeStore**</span><span class="sxs-lookup"><span data-stu-id="3c01a-134">**DataLakeStore**</span></span>
- <span data-ttu-id="3c01a-135">Remove-AzureRmDataLakeStoreItemAclEntry</span><span class="sxs-lookup"><span data-stu-id="3c01a-135">Remove-AzureRmDataLakeStoreItemAclEntry</span></span>
- <span data-ttu-id="3c01a-136">Set-AzureRmDataLakeStoreItemAcl</span><span class="sxs-lookup"><span data-stu-id="3c01a-136">Set-AzureRmDataLakeStoreItemAcl</span></span>
- <span data-ttu-id="3c01a-137">Set-AzureRmDataLakeStoreItemAclEntry</span><span class="sxs-lookup"><span data-stu-id="3c01a-137">Set-AzureRmDataLakeStoreItemAclEntry</span></span>
- <span data-ttu-id="3c01a-138">Set-AzureRmDataLakeStoreItemOwner</span><span class="sxs-lookup"><span data-stu-id="3c01a-138">Set-AzureRmDataLakeStoreItemOwner</span></span>

<span data-ttu-id="3c01a-139">**OperationalInsights**</span><span class="sxs-lookup"><span data-stu-id="3c01a-139">**OperationalInsights**</span></span>
- <span data-ttu-id="3c01a-140">Remove-AzureRmOperationalInsightsSavedSearch</span><span class="sxs-lookup"><span data-stu-id="3c01a-140">Remove-AzureRmOperationalInsightsSavedSearch</span></span>

<span data-ttu-id="3c01a-141">**Profil**</span><span class="sxs-lookup"><span data-stu-id="3c01a-141">**Profile**</span></span>
- <span data-ttu-id="3c01a-142">Remove-AzureRmEnvironment</span><span class="sxs-lookup"><span data-stu-id="3c01a-142">Remove-AzureRmEnvironment</span></span>

<span data-ttu-id="3c01a-143">**RedisCache**</span><span class="sxs-lookup"><span data-stu-id="3c01a-143">**RedisCache**</span></span>
- <span data-ttu-id="3c01a-144">Remove-AzureRmRedisCacheDiagnostics</span><span class="sxs-lookup"><span data-stu-id="3c01a-144">Remove-AzureRmRedisCacheDiagnostics</span></span>

<span data-ttu-id="3c01a-145">**Ressources**</span><span class="sxs-lookup"><span data-stu-id="3c01a-145">**Resources**</span></span>
- <span data-ttu-id="3c01a-146">Register-AzureRmProviderFeature</span><span class="sxs-lookup"><span data-stu-id="3c01a-146">Register-AzureRmProviderFeature</span></span>
- <span data-ttu-id="3c01a-147">Register-AzureRmResourceProvider</span><span class="sxs-lookup"><span data-stu-id="3c01a-147">Register-AzureRmResourceProvider</span></span>
- <span data-ttu-id="3c01a-148">Remove-AzureRmADServicePrincipal</span><span class="sxs-lookup"><span data-stu-id="3c01a-148">Remove-AzureRmADServicePrincipal</span></span>
- <span data-ttu-id="3c01a-149">Remove-AzureRmPolicyAssignment</span><span class="sxs-lookup"><span data-stu-id="3c01a-149">Remove-AzureRmPolicyAssignment</span></span>
- <span data-ttu-id="3c01a-150">Remove-AzureRmResourceGroupDeployment</span><span class="sxs-lookup"><span data-stu-id="3c01a-150">Remove-AzureRmResourceGroupDeployment</span></span>
- <span data-ttu-id="3c01a-151">Remove-AzureRmRoleAssignment</span><span class="sxs-lookup"><span data-stu-id="3c01a-151">Remove-AzureRmRoleAssignment</span></span>
- <span data-ttu-id="3c01a-152">Stop-AzureRmResourceGroupDeployment</span><span class="sxs-lookup"><span data-stu-id="3c01a-152">Stop-AzureRmResourceGroupDeployment</span></span>
- <span data-ttu-id="3c01a-153">Unregister-AzureRmResourceProvider</span><span class="sxs-lookup"><span data-stu-id="3c01a-153">Unregister-AzureRmResourceProvider</span></span>

<span data-ttu-id="3c01a-154">**Stockage**</span><span class="sxs-lookup"><span data-stu-id="3c01a-154">**Storage**</span></span>
- <span data-ttu-id="3c01a-155">Remove-AzureStorageContainerStoredAccessPolicy</span><span class="sxs-lookup"><span data-stu-id="3c01a-155">Remove-AzureStorageContainerStoredAccessPolicy</span></span>
- <span data-ttu-id="3c01a-156">Remove-AzureStorageQueueStoredAccessPolicy</span><span class="sxs-lookup"><span data-stu-id="3c01a-156">Remove-AzureStorageQueueStoredAccessPolicy</span></span>
- <span data-ttu-id="3c01a-157">Remove-AzureStorageShareStoredAccessPolicy</span><span class="sxs-lookup"><span data-stu-id="3c01a-157">Remove-AzureStorageShareStoredAccessPolicy</span></span>
- <span data-ttu-id="3c01a-158">Remove-AzureStorageTableStoredAccessPolicy</span><span class="sxs-lookup"><span data-stu-id="3c01a-158">Remove-AzureStorageTableStoredAccessPolicy</span></span>

<span data-ttu-id="3c01a-159">**StreamAnalytics**</span><span class="sxs-lookup"><span data-stu-id="3c01a-159">**StreamAnalytics**</span></span>
- <span data-ttu-id="3c01a-160">Remove-AzureRmStreamAnalyticsFunction</span><span class="sxs-lookup"><span data-stu-id="3c01a-160">Remove-AzureRmStreamAnalyticsFunction</span></span>
- <span data-ttu-id="3c01a-161">Remove-AzureRmStreamAnalyticsInput</span><span class="sxs-lookup"><span data-stu-id="3c01a-161">Remove-AzureRmStreamAnalyticsInput</span></span>
- <span data-ttu-id="3c01a-162">Remove-AzureRmStreamAnalyticsJob</span><span class="sxs-lookup"><span data-stu-id="3c01a-162">Remove-AzureRmStreamAnalyticsJob</span></span>
- <span data-ttu-id="3c01a-163">Remove-AzureRmStreamAnalyticsOutput</span><span class="sxs-lookup"><span data-stu-id="3c01a-163">Remove-AzureRmStreamAnalyticsOutput</span></span>

<span data-ttu-id="3c01a-164">**Tag**</span><span class="sxs-lookup"><span data-stu-id="3c01a-164">**Tag**</span></span>
- <span data-ttu-id="3c01a-165">Remove-AzureRmTag</span><span class="sxs-lookup"><span data-stu-id="3c01a-165">Remove-AzureRmTag</span></span>

<br>

<span data-ttu-id="3c01a-166">Si vous possédez un script qui utilise l’une des applet de commande ci-dessus, la dernière modification peut être corrigée tout simplement, par la suppression du paramètre `Force`.</span><span class="sxs-lookup"><span data-stu-id="3c01a-166">If you have a script that uses any of the above cmdlets, the breaking change can be fixed by simply removing the `Force` parameter.</span></span>

```powershell
# Old
New-AzureRmResourceGroup -Name $resourceGroupName -Location $location -Force

# New
New-AzureRmResourceGroup -Name $resourceGroupName -Location $location
```

<br>

## <a name="change-of-tag-parameters"></a><span data-ttu-id="3c01a-167">Modification des paramètres Tag</span><span class="sxs-lookup"><span data-stu-id="3c01a-167">Change of Tag parameters</span></span>

<span data-ttu-id="3c01a-168">Dans cette version, le nom du paramètre `Tags` est devenu `Tag`, tandis que le type est passé de `Hashtable[]` à `Hashtable`, ce qui a entraîné la modification du format des paires clé-valeur.</span><span class="sxs-lookup"><span data-stu-id="3c01a-168">This release, the `Tags` parameter name was changed to `Tag`, and the type was changed from `Hashtable[]` to `Hashtable`, changing the format of the key-value pairings.</span></span>

<span data-ttu-id="3c01a-169">Auparavant, chaque entrée de l’instance `Hashtable[]` représentait une seule paire clé-valeur :</span><span class="sxs-lookup"><span data-stu-id="3c01a-169">Previously, each entry in the `Hashtable[]` represented a single key-value pairing:</span></span>

```powershell
$tags = @{ Name = "test1"; Value = "testval1" }, @{ Name = "test2", Value = "testval2" }
$tags[0].Name  # Key for the first entry, "test1"
$tags[0].Value # Value for the first entry, "testval1"
$tags[1].Name  # Key for the second entry, "test2"
$tags[1].Value # Value for the second entry, "testval2"
```

<span data-ttu-id="3c01a-170">Désormais, `Name` et `Value` ne sont plus nécessaires, ce qui permet de créer des paires clé-valeur par l’affectation de `Key = "Value"` dans l’instance `Hashtable` :</span><span class="sxs-lookup"><span data-stu-id="3c01a-170">Now, `Name` and `Value` are no longer necessary, allowing for key-value pairings to be created by assigning `Key = "Value"` in the `Hashtable`:</span></span>

```powershell
$tag = @{ test1 = "testval1"; test2 = "testval2" }
$tag["test1"] # Gets the value associated with the key "test1"
$tag["test2"] # Gets the value associated with the key "test2"
```

<span data-ttu-id="3c01a-171">Les applets de commande suivantes sont affectées par cette modification :</span><span class="sxs-lookup"><span data-stu-id="3c01a-171">The following cmdlets are affected by this change:</span></span>

<span data-ttu-id="3c01a-172">**Batch**</span><span class="sxs-lookup"><span data-stu-id="3c01a-172">**Batch**</span></span>
- <span data-ttu-id="3c01a-173">Get-AzureRmBatchAccount</span><span class="sxs-lookup"><span data-stu-id="3c01a-173">Get-AzureRmBatchAccount</span></span>
- <span data-ttu-id="3c01a-174">New-AzureRmBatchAccount</span><span class="sxs-lookup"><span data-stu-id="3c01a-174">New-AzureRmBatchAccount</span></span>
- <span data-ttu-id="3c01a-175">Set-AzureRmBatchAccount</span><span class="sxs-lookup"><span data-stu-id="3c01a-175">Set-AzureRmBatchAccount</span></span>

<span data-ttu-id="3c01a-176">**Calcul**</span><span class="sxs-lookup"><span data-stu-id="3c01a-176">**Compute**</span></span>
- <span data-ttu-id="3c01a-177">New-AzureRmVM</span><span class="sxs-lookup"><span data-stu-id="3c01a-177">New-AzureRmVM</span></span>
- <span data-ttu-id="3c01a-178">Update-AzureRmVM</span><span class="sxs-lookup"><span data-stu-id="3c01a-178">Update-AzureRmVM</span></span>

<span data-ttu-id="3c01a-179">**DataLakeAnalytics**</span><span class="sxs-lookup"><span data-stu-id="3c01a-179">**DataLakeAnalytics**</span></span>
- <span data-ttu-id="3c01a-180">New-AzureRmDataLakeAnalyticsAccount</span><span class="sxs-lookup"><span data-stu-id="3c01a-180">New-AzureRmDataLakeAnalyticsAccount</span></span>
- <span data-ttu-id="3c01a-181">Set-AzureRmDataLakeAnalyticsAccount</span><span class="sxs-lookup"><span data-stu-id="3c01a-181">Set-AzureRmDataLakeAnalyticsAccount</span></span>

<span data-ttu-id="3c01a-182">**DataLakeStore**</span><span class="sxs-lookup"><span data-stu-id="3c01a-182">**DataLakeStore**</span></span>
- <span data-ttu-id="3c01a-183">New-AzureRmDataLakeStoreAccount</span><span class="sxs-lookup"><span data-stu-id="3c01a-183">New-AzureRmDataLakeStoreAccount</span></span>
- <span data-ttu-id="3c01a-184">Set-AzureRmDataLakeStoreAccount</span><span class="sxs-lookup"><span data-stu-id="3c01a-184">Set-AzureRmDataLakeStoreAccount</span></span>

<span data-ttu-id="3c01a-185">**Dns**</span><span class="sxs-lookup"><span data-stu-id="3c01a-185">**Dns**</span></span>
- <span data-ttu-id="3c01a-186">New-AzureRmDnsZone</span><span class="sxs-lookup"><span data-stu-id="3c01a-186">New-AzureRmDnsZone</span></span>
- <span data-ttu-id="3c01a-187">Set-AzureRmDnsZone</span><span class="sxs-lookup"><span data-stu-id="3c01a-187">Set-AzureRmDnsZone</span></span>

<span data-ttu-id="3c01a-188">**Coffre de clés**</span><span class="sxs-lookup"><span data-stu-id="3c01a-188">**KeyVault**</span></span>
- <span data-ttu-id="3c01a-189">Get-AzureRmKeyVault</span><span class="sxs-lookup"><span data-stu-id="3c01a-189">Get-AzureRmKeyVault</span></span>
- <span data-ttu-id="3c01a-190">New-AzureRmKeyVault</span><span class="sxs-lookup"><span data-stu-id="3c01a-190">New-AzureRmKeyVault</span></span>

<span data-ttu-id="3c01a-191">**Réseau**</span><span class="sxs-lookup"><span data-stu-id="3c01a-191">**Network**</span></span>
- <span data-ttu-id="3c01a-192">New-AzureRmApplicationGateway</span><span class="sxs-lookup"><span data-stu-id="3c01a-192">New-AzureRmApplicationGateway</span></span>
- <span data-ttu-id="3c01a-193">New-AzureRmExpressRouteCircuit</span><span class="sxs-lookup"><span data-stu-id="3c01a-193">New-AzureRmExpressRouteCircuit</span></span>
- <span data-ttu-id="3c01a-194">New-AzureRmLoadBalancer</span><span class="sxs-lookup"><span data-stu-id="3c01a-194">New-AzureRmLoadBalancer</span></span>
- <span data-ttu-id="3c01a-195">New-AzureRmLocalNetworkGateway</span><span class="sxs-lookup"><span data-stu-id="3c01a-195">New-AzureRmLocalNetworkGateway</span></span>
- <span data-ttu-id="3c01a-196">New-AzureRmNetworkInterface</span><span class="sxs-lookup"><span data-stu-id="3c01a-196">New-AzureRmNetworkInterface</span></span>
- <span data-ttu-id="3c01a-197">New-AzureRmNetworkSecurityGroup</span><span class="sxs-lookup"><span data-stu-id="3c01a-197">New-AzureRmNetworkSecurityGroup</span></span>
- <span data-ttu-id="3c01a-198">New-AzureRmPublicIpAddress</span><span class="sxs-lookup"><span data-stu-id="3c01a-198">New-AzureRmPublicIpAddress</span></span>
- <span data-ttu-id="3c01a-199">New-AzureRmRouteTable</span><span class="sxs-lookup"><span data-stu-id="3c01a-199">New-AzureRmRouteTable</span></span>
- <span data-ttu-id="3c01a-200">New-AzureRmVirtualNetwork</span><span class="sxs-lookup"><span data-stu-id="3c01a-200">New-AzureRmVirtualNetwork</span></span>
- <span data-ttu-id="3c01a-201">New-AzureRmVirtualNetworkGateway</span><span class="sxs-lookup"><span data-stu-id="3c01a-201">New-AzureRmVirtualNetworkGateway</span></span>
- <span data-ttu-id="3c01a-202">New-AzureRmVirtualNetworkGatewayConnection</span><span class="sxs-lookup"><span data-stu-id="3c01a-202">New-AzureRmVirtualNetworkGatewayConnection</span></span>
- <span data-ttu-id="3c01a-203">New-AzureRmVirtualNetworkPeering</span><span class="sxs-lookup"><span data-stu-id="3c01a-203">New-AzureRmVirtualNetworkPeering</span></span>

<span data-ttu-id="3c01a-204">**Ressources**</span><span class="sxs-lookup"><span data-stu-id="3c01a-204">**Resources**</span></span>
- <span data-ttu-id="3c01a-205">Recherche-AzureRmResource</span><span class="sxs-lookup"><span data-stu-id="3c01a-205">Find-AzureRmResource</span></span>
- <span data-ttu-id="3c01a-206">Recherche-AzureRmResourceGroup</span><span class="sxs-lookup"><span data-stu-id="3c01a-206">Find-AzureRmResourceGroup</span></span>
- <span data-ttu-id="3c01a-207">New-AzureRmResource</span><span class="sxs-lookup"><span data-stu-id="3c01a-207">New-AzureRmResource</span></span>
- <span data-ttu-id="3c01a-208">New-AzureRmResourceGroup</span><span class="sxs-lookup"><span data-stu-id="3c01a-208">New-AzureRmResourceGroup</span></span>
- <span data-ttu-id="3c01a-209">Set-AzureRmResource</span><span class="sxs-lookup"><span data-stu-id="3c01a-209">Set-AzureRmResource</span></span>
- <span data-ttu-id="3c01a-210">Set-AzureRmResourceGroup</span><span class="sxs-lookup"><span data-stu-id="3c01a-210">Set-AzureRmResourceGroup</span></span>

<span data-ttu-id="3c01a-211">**SQL**</span><span class="sxs-lookup"><span data-stu-id="3c01a-211">**SQL**</span></span>
- <span data-ttu-id="3c01a-212">New-AzureRmSqlDatabase</span><span class="sxs-lookup"><span data-stu-id="3c01a-212">New-AzureRmSqlDatabase</span></span>
- <span data-ttu-id="3c01a-213">New-AzureRmSqlDatabaseCopy</span><span class="sxs-lookup"><span data-stu-id="3c01a-213">New-AzureRmSqlDatabaseCopy</span></span>
- <span data-ttu-id="3c01a-214">New-AzureRmSqlDatabaseSecondary</span><span class="sxs-lookup"><span data-stu-id="3c01a-214">New-AzureRmSqlDatabaseSecondary</span></span>
- <span data-ttu-id="3c01a-215">New-AzureRmSqlElasticPool</span><span class="sxs-lookup"><span data-stu-id="3c01a-215">New-AzureRmSqlElasticPool</span></span>
- <span data-ttu-id="3c01a-216">New-AzureRmSqlServer</span><span class="sxs-lookup"><span data-stu-id="3c01a-216">New-AzureRmSqlServer</span></span>
- <span data-ttu-id="3c01a-217">Set-AzureRmSqlDatabase</span><span class="sxs-lookup"><span data-stu-id="3c01a-217">Set-AzureRmSqlDatabase</span></span>
- <span data-ttu-id="3c01a-218">Set-AzureRmSqlElasticPool</span><span class="sxs-lookup"><span data-stu-id="3c01a-218">Set-AzureRmSqlElasticPool</span></span>
- <span data-ttu-id="3c01a-219">Set-AzureRmSqlServer</span><span class="sxs-lookup"><span data-stu-id="3c01a-219">Set-AzureRmSqlServer</span></span>

<span data-ttu-id="3c01a-220">**Stockage**</span><span class="sxs-lookup"><span data-stu-id="3c01a-220">**Storage**</span></span>
- <span data-ttu-id="3c01a-221">New-AzureRmStorageAccount</span><span class="sxs-lookup"><span data-stu-id="3c01a-221">New-AzureRmStorageAccount</span></span>
- <span data-ttu-id="3c01a-222">Set-AzureRmStorageAccount</span><span class="sxs-lookup"><span data-stu-id="3c01a-222">Set-AzureRmStorageAccount</span></span>

<span data-ttu-id="3c01a-223">**TrafficManager**</span><span class="sxs-lookup"><span data-stu-id="3c01a-223">**TrafficManager**</span></span>
- <span data-ttu-id="3c01a-224">New-AzureRmTrafficManagerProfile</span><span class="sxs-lookup"><span data-stu-id="3c01a-224">New-AzureRmTrafficManagerProfile</span></span>

<br>

<span data-ttu-id="3c01a-225">Si vous possédez un script qui utilise l’une des applets de commande ci-dessus, la dernière modification peut être corrigée par la modification du paramètre `Tags` en `Tag`, ainsi que par l’adoption du nouveau format pour `Tag`.</span><span class="sxs-lookup"><span data-stu-id="3c01a-225">If you have a script that uses any of the above cmdlets, the breaking change can be fixed by changing the `Tags` parameter to `Tag`, as well as changing the `Tag` to the new format.</span></span>

```powershell
# Old
New-AzureRmResourceGroup -Name $resourceGroupName -Location -location -Tags @{ Name = "testtag"; Value = "testval" }

# New
New-AzureRmResourceGroup -Name $resourceGroupName -Location -location -Tag @{ testtag = "testval" }
```

<br>

## <a name="breaking-changes-to-storage-cmdlets"></a><span data-ttu-id="3c01a-226">Dernières modifications des applets de commande Storage</span><span class="sxs-lookup"><span data-stu-id="3c01a-226">Breaking changes to Storage cmdlets</span></span>

<span data-ttu-id="3c01a-227">Les applets de commande suivantes affectaient cette version :</span><span class="sxs-lookup"><span data-stu-id="3c01a-227">The following cmdlets were affected this release:</span></span>

<span data-ttu-id="3c01a-228">**Get-AzureRmStorageAccountKey**</span><span class="sxs-lookup"><span data-stu-id="3c01a-228">**Get-AzureRmStorageAccountKey**</span></span>
- <span data-ttu-id="3c01a-229">L’applet de commande renvoie désormais une liste de clés, plutôt qu’un objet comportant des propriétés pour chaque clé.</span><span class="sxs-lookup"><span data-stu-id="3c01a-229">The cmdlet now returns a list of keys, rather than an object with properties for each key</span></span>

```powershell
# Old
$key = (Get-AzureRmStorageAccountKey -ResourceGroupName $resourceGroupName -Name $accountName).Key1

# New
$key = (Get-AzureRmStorageAccountKey -ResourceGroupName $resourceGroupName -Name $accountName)[0].Value
```

<span data-ttu-id="3c01a-230">**New-AzureRmStorageAccountKey**</span><span class="sxs-lookup"><span data-stu-id="3c01a-230">**New-AzureRmStorageAccountKey**</span></span>
- <span data-ttu-id="3c01a-231">Le champ `StorageAccountRegenerateKeyResponse` dans la sortie de cette applet de commande est renommé `StorageAccountListKeysResults` ; il s’agit désormais d’une liste de clés, non pas d’un objet comportant des propriétés pour chaque clé.</span><span class="sxs-lookup"><span data-stu-id="3c01a-231">`StorageAccountRegenerateKeyResponse` field in output of this cmdlet is renamed to `StorageAccountListKeysResults`, which is now a list of keys rather than an object with properties for each key</span></span>

```powershell
# Old
$key = (New-AzureRmStorageAccountKey -ResourceGroupName $resourceGroupName -Name $accountName).StorageAccountKeys.Key1

# New
$key = (New-AzureRmStorageAccountKey -ResourceGroupName $resourceGroupName -Name $accountName).Keys[0].Value
```

<span data-ttu-id="3c01a-232">**New/Get/Set-AzureRmStorageAccount**</span><span class="sxs-lookup"><span data-stu-id="3c01a-232">**New/Get/Set-AzureRmStorageAccount**</span></span>
- <span data-ttu-id="3c01a-233">Le champ `AccountType` dans la sortie de cette applet de commande est renommé `Sku.Name`.</span><span class="sxs-lookup"><span data-stu-id="3c01a-233">`AccountType` field in output of this cmdlet is renamed to `Sku.Name`</span></span>
- <span data-ttu-id="3c01a-234">Le type de sortie pour les points de terminaison PrimaryEndpoints/Secondary endpoints blob/table/queue/file a été modifié de `Uri` en `String`.</span><span class="sxs-lookup"><span data-stu-id="3c01a-234">Output type for PrimaryEndpoints/Secondary endpoints blob/table/queue/file changed from `Uri` to `String`</span></span>

```powershell
# Old
$accountType = (Get-AzureRmStorageAccount -ResourceGroupName $resourceGroupName -Name $accountName).AccountType

# New
$accountType = (Get-AzureRmStorageAccount -ResourceGroupName $resourceGroupName -Name $accountName).Sku.Name
```

```powershell
# Old 
$blobEndpoint = (Get-AzureRmStorageAccount -ResourceGroupName $resourceGroupName -Name $accountName).PrimaryEndpoints.Blob.ToString()
$blobEndpoint = (Get-AzureRmStorageAccount -ResourceGroupName $resourceGroupName -Name $accountName).PrimaryEndpoints.Blob.AbsolutePath

# New
$blobEndpoint = (Get-AzureRmStorageAccount -ResourceGroupName $resourceGroupName -Name $accountName).PrimaryEndpoints.Blob.ToString()
$blobEndpoint = (Get-AzureRmStorageAccount -ResourceGroupName $resourceGroupName -Name $accountName).PrimaryEndpoints.Blob
```

<br>

## <a name="breaking-changes-to-ad-cmdlets"></a><span data-ttu-id="3c01a-235">Dernières modifications des applets de commande AD</span><span class="sxs-lookup"><span data-stu-id="3c01a-235">Breaking changes to AD cmdlets</span></span>

<span data-ttu-id="3c01a-236">Les applets de commande suivantes affectaient cette version :</span><span class="sxs-lookup"><span data-stu-id="3c01a-236">The following cmdlets were affected this release:</span></span>

<span data-ttu-id="3c01a-237">**Get-AzureRMADServicePrincipal**</span><span class="sxs-lookup"><span data-stu-id="3c01a-237">**Get-AzureRMADServicePrincipal**</span></span>
- <span data-ttu-id="3c01a-238">Le champ `ServicePrincipalName` dans la sortie de cette applet de commande a été renommé `ServicePrincipalNames` ; il s’agit désormais d’une collection.</span><span class="sxs-lookup"><span data-stu-id="3c01a-238">`ServicePrincipalName` field in output of this cmdlet is renamed to `ServicePrincipalNames` and is now a collection.</span></span> <span data-ttu-id="3c01a-239">Il affiche désormais `ApplicationId` également en tant qu’un des SPN, avec l’élément identifierUri.</span><span class="sxs-lookup"><span data-stu-id="3c01a-239">It now displays `ApplicationId` also as one of the SPN, along with the identifierUri.</span></span>

```powershell
# Old
$servicePrincipals = Get-AzureRmADServicePrincipal -SearchString $displayName
$spn = $servicePrincipals[0].ServicePrincipalName

# New
$servicePrincipals = Get-AzureRmADServicePrincipal -SearchString $displayName
$spn = $servicePrincipals[0].ServicePrincipalNames[0]
```

<span data-ttu-id="3c01a-240">**Get-AzureRmADApplication**</span><span class="sxs-lookup"><span data-stu-id="3c01a-240">**Get-AzureRmADApplication**</span></span>
- <span data-ttu-id="3c01a-241">Le paramètre `ApplicationObjectId` est renommé `ObjectId`.</span><span class="sxs-lookup"><span data-stu-id="3c01a-241">Parameter `ApplicationObjectId` is renamed to `ObjectId`.</span></span>
- <span data-ttu-id="3c01a-242">Dans la sortie de cette applet de commande, `ApplicationObjectId` est renommé `ObjectId`.</span><span class="sxs-lookup"><span data-stu-id="3c01a-242">In output of this cmdlet, `ApplicationObjectId` is renamed to `ObjectId`.</span></span>

```powershell
# Old
$app = Get-AzureRmADApplication -ApplicationObjectId $applicationObjectId
$objectId = $app.ApplicationObjectId

# New
$app = Get-AzureRmADApplication -ObjectId $objectId
$objectId = $app.ObjectId
```

<span data-ttu-id="3c01a-243">**Remove-AzureRmADApplication**</span><span class="sxs-lookup"><span data-stu-id="3c01a-243">**Remove-AzureRmADApplication**</span></span>
- <span data-ttu-id="3c01a-244">Le paramètre `ApplicationObjectId` est renommé `ObjectId`.</span><span class="sxs-lookup"><span data-stu-id="3c01a-244">Parameter `ApplicationObjectId` is renamed to `ObjectId`.</span></span>

```powershell
# Old
$app = Remove-AzureRmADApplication -ApplicationObjectId $applicationObjectId -Force

# New
$app = Remove-AzureRmADApplication -ObjectId $objectId -Force
```

<span data-ttu-id="3c01a-245">**New-AzureRmADApplication**</span><span class="sxs-lookup"><span data-stu-id="3c01a-245">**New-AzureRmADApplication**</span></span>
- <span data-ttu-id="3c01a-246">Dans la sortie de cette applet de commande, `ApplicationObjectId` est renommé `ObjectId`.</span><span class="sxs-lookup"><span data-stu-id="3c01a-246">In output of this cmdlet, `ApplicationObjectId` is renamed to `ObjectId`.</span></span>
- <span data-ttu-id="3c01a-247">Les paramètres `KeyValue`, `KeyUsage`, `KeyType` sont supprimés.</span><span class="sxs-lookup"><span data-stu-id="3c01a-247">`KeyValue`, `KeyUsage`, `KeyType` parameters are removed.</span></span>

```powershell
# Old
$app = New-AzureRmADApplication -DisplayName $displayName -HomePage $homePage -IdentifierUris $identifierUris -KeyValue $kv -KeyType $kt -KeyUsage $ku
$id = $app.ApplicationObjectId

# New
$app = New-AzureRmADApplication -DisplayName $displayName -HomePage $homePage -IdentifierUris $identifierUris
$id = $app.ObjectId
New-AzureRmADAppCredential -ObjectId $id -Password $kv
```

<span data-ttu-id="3c01a-248">**Get-AzureRmADGroup**</span><span class="sxs-lookup"><span data-stu-id="3c01a-248">**Get-AzureRmADGroup**</span></span>
- <span data-ttu-id="3c01a-249">Le champ `Mail` est supprimé de la sortie.</span><span class="sxs-lookup"><span data-stu-id="3c01a-249">`Mail` field is removed from the output.</span></span>

<span data-ttu-id="3c01a-250">**Get-AzureRmADUser**</span><span class="sxs-lookup"><span data-stu-id="3c01a-250">**Get-AzureRmADUser**</span></span>
- <span data-ttu-id="3c01a-251">Le champ `Mail` est supprimé de la sortie.</span><span class="sxs-lookup"><span data-stu-id="3c01a-251">`Mail` field is removed from the output.</span></span>

<span data-ttu-id="3c01a-252">**New-AzureRmADServicePrincipal**</span><span class="sxs-lookup"><span data-stu-id="3c01a-252">**New-AzureRmADServicePrincipal**</span></span>
- <span data-ttu-id="3c01a-253">Le paramètre `DisableAccount` est supprimé.</span><span class="sxs-lookup"><span data-stu-id="3c01a-253">Removed `DisableAccount` parameter.</span></span>

```powershell
# Old
$servicePrincipal = New-AzureRmADServicePrincipal -DisplayName $displayName -Password $password -DisableAccount true

# New
$servicePrincipal = New-AzureRmADServicePrincipal -DisplayName $displayName -Password $password
Remove-AzureRmADServicePrincipal -ObjectId $servicePrincipal.ObjectId
```