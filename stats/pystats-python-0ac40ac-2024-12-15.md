## Execution counts

<details>
<summary> Execution counts for Tier 1 instructions. </summary>


The "miss ratio" column shows the percentage of times the instruction
executed that it deoptimized. When this happens, the base unspecialized
instruction is not counted.

<table>
<thead>
<tr>
<th align="left">Name</th>
<th align="right">Count</th>
<th align="right">Self</th>
<th align="right">Cumulative</th>
<th align="right">Miss ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">19,955,920,541</td>
<td align="right">18.6%</td>
<td align="right">18.6%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">6,633,000,817</td>
<td align="right">6.2%</td>
<td align="right">24.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">4,810,862,942</td>
<td align="right">4.5%</td>
<td align="right">29.3%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">4,753,247,759</td>
<td align="right">4.4%</td>
<td align="right">33.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">3,833,574,454</td>
<td align="right">3.6%</td>
<td align="right">37.3%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">3,442,385,919</td>
<td align="right">3.2%</td>
<td align="right">40.5%</td>
<td align="right">5.6%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">3,298,631,271</td>
<td align="right">3.1%</td>
<td align="right">43.6%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">3,105,894,309</td>
<td align="right">2.9%</td>
<td align="right">46.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">3,004,605,675</td>
<td align="right">2.8%</td>
<td align="right">49.3%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">2,964,868,271</td>
<td align="right">2.8%</td>
<td align="right">52.1%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">2,492,171,103</td>
<td align="right">2.3%</td>
<td align="right">54.4%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">2,353,224,892</td>
<td align="right">2.2%</td>
<td align="right">56.6%</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">2,211,266,571</td>
<td align="right">2.1%</td>
<td align="right">58.6%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">1,990,539,143</td>
<td align="right">1.9%</td>
<td align="right">60.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">1,875,031,159</td>
<td align="right">1.7%</td>
<td align="right">62.3%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">1,867,378,767</td>
<td align="right">1.7%</td>
<td align="right">64.0%</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">1,507,887,606</td>
<td align="right">1.4%</td>
<td align="right">65.4%</td>
<td align="right">9.3%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">1,277,765,683</td>
<td align="right">1.2%</td>
<td align="right">66.6%</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">1,234,790,524</td>
<td align="right">1.2%</td>
<td align="right">67.7%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">1,218,579,233</td>
<td align="right">1.1%</td>
<td align="right">68.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">1,176,202,394</td>
<td align="right">1.1%</td>
<td align="right">70.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">1,072,840,900</td>
<td align="right">1.0%</td>
<td align="right">71.0%</td>
<td align="right">6.0%</td>
</tr>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">1,027,780,902</td>
<td align="right">1.0%</td>
<td align="right">71.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">968,362,094</td>
<td align="right">0.9%</td>
<td align="right">72.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">950,549,500</td>
<td align="right">0.9%</td>
<td align="right">73.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">941,396,841</td>
<td align="right">0.9%</td>
<td align="right">74.6%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">925,508,201</td>
<td align="right">0.9%</td>
<td align="right">75.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_FLOAT</td>
<td align="right">922,688,640</td>
<td align="right">0.9%</td>
<td align="right">76.3%</td>
<td align="right">0.8%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">913,672,250</td>
<td align="right">0.9%</td>
<td align="right">77.2%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">857,639,531</td>
<td align="right">0.8%</td>
<td align="right">78.0%</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">856,089,842</td>
<td align="right">0.8%</td>
<td align="right">78.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">790,786,228</td>
<td align="right">0.7%</td>
<td align="right">79.5%</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">788,909,811</td>
<td align="right">0.7%</td>
<td align="right">80.3%</td>
<td align="right">1.0%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">717,813,516</td>
<td align="right">0.7%</td>
<td align="right">80.9%</td>
<td align="right">8.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">707,375,920</td>
<td align="right">0.7%</td>
<td align="right">81.6%</td>
<td align="right">10.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">685,036,240</td>
<td align="right">0.6%</td>
<td align="right">82.2%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">645,797,702</td>
<td align="right">0.6%</td>
<td align="right">82.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">577,619,693</td>
<td align="right">0.5%</td>
<td align="right">83.4%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">563,847,031</td>
<td align="right">0.5%</td>
<td align="right">83.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">550,105,070</td>
<td align="right">0.5%</td>
<td align="right">84.4%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">538,773,723</td>
<td align="right">0.5%</td>
<td align="right">84.9%</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">524,452,125</td>
<td align="right">0.5%</td>
<td align="right">85.4%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_INT</td>
<td align="right">476,666,430</td>
<td align="right">0.4%</td>
<td align="right">85.8%</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">SEND_GEN</td>
<td align="right">458,975,644</td>
<td align="right">0.4%</td>
<td align="right">86.3%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_FLOAT</td>
<td align="right">455,193,247</td>
<td align="right">0.4%</td>
<td align="right">86.7%</td>
<td align="right">1.5%</td>
</tr>
<tr>
<td align="left">IS_OP</td>
<td align="right">452,953,083</td>
<td align="right">0.4%</td>
<td align="right">87.1%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">FOR_ITER_RANGE</td>
<td align="right">444,459,081</td>
<td align="right">0.4%</td>
<td align="right">87.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE</td>
<td align="right">403,344,383</td>
<td align="right">0.4%</td>
<td align="right">87.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">387,366,636</td>
<td align="right">0.4%</td>
<td align="right">88.3%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_NO_INTERRUPT</td>
<td align="right">377,713,649</td>
<td align="right">0.4%</td>
<td align="right">88.6%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CONTAINS_OP_SET</td>
<td align="right">366,897,831</td>
<td align="right">0.3%</td>
<td align="right">89.0%</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">CALL_TYPE_1</td>
<td align="right">355,757,645</td>
<td align="right">0.3%</td>
<td align="right">89.3%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">350,048,643</td>
<td align="right">0.3%</td>
<td align="right">89.6%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_ATTR_CLASS</td>
<td align="right">319,180,938</td>
<td align="right">0.3%</td>
<td align="right">89.9%</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">312,099,053</td>
<td align="right">0.3%</td>
<td align="right">90.2%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">310,689,486</td>
<td align="right">0.3%</td>
<td align="right">90.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_FLOAT</td>
<td align="right">282,313,071</td>
<td align="right">0.3%</td>
<td align="right">90.8%</td>
<td align="right">5.3%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_SLOT</td>
<td align="right">279,941,442</td>
<td align="right">0.3%</td>
<td align="right">91.0%</td>
<td align="right">3.0%</td>
</tr>
<tr>
<td align="left">CALL_LEN</td>
<td align="right">275,278,636</td>
<td align="right">0.3%</td>
<td align="right">91.3%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_LIST_INT</td>
<td align="right">270,385,983</td>
<td align="right">0.3%</td>
<td align="right">91.5%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_INT</td>
<td align="right">269,994,238</td>
<td align="right">0.3%</td>
<td align="right">91.8%</td>
<td align="right">3.2%</td>
</tr>
<tr>
<td align="left">JUMP_FORWARD</td>
<td align="right">265,038,066</td>
<td align="right">0.2%</td>
<td align="right">92.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">255,986,676</td>
<td align="right">0.2%</td>
<td align="right">92.3%</td>
<td align="right">25.3%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">254,599,154</td>
<td align="right">0.2%</td>
<td align="right">92.5%</td>
<td align="right">10.2%</td>
</tr>
<tr>
<td align="left">CALL_PY_GENERAL</td>
<td align="right">234,244,673</td>
<td align="right">0.2%</td>
<td align="right">92.7%</td>
<td align="right">1.0%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NOT_NONE</td>
<td align="right">233,760,799</td>
<td align="right">0.2%</td>
<td align="right">93.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_TUPLE_INT</td>
<td align="right">228,528,054</td>
<td align="right">0.2%</td>
<td align="right">93.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_LIST</td>
<td align="right">228,349,489</td>
<td align="right">0.2%</td>
<td align="right">93.4%</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">207,641,118</td>
<td align="right">0.2%</td>
<td align="right">93.6%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL_INT</td>
<td align="right">207,066,869</td>
<td align="right">0.2%</td>
<td align="right">93.8%</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_DICT</td>
<td align="right">198,785,285</td>
<td align="right">0.2%</td>
<td align="right">94.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">198,023,940</td>
<td align="right">0.2%</td>
<td align="right">94.1%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">198,005,986</td>
<td align="right">0.2%</td>
<td align="right">94.3%</td>
<td align="right">6.6%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_STR</td>
<td align="right">192,364,059</td>
<td align="right">0.2%</td>
<td align="right">94.5%</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">191,090,328</td>
<td align="right">0.2%</td>
<td align="right">94.7%</td>
<td align="right">29.2%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_DICT</td>
<td align="right">189,161,706</td>
<td align="right">0.2%</td>
<td align="right">94.9%</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">186,154,901</td>
<td align="right">0.2%</td>
<td align="right">95.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BUILD_LIST</td>
<td align="right">184,675,659</td>
<td align="right">0.2%</td>
<td align="right">95.2%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">END_SEND</td>
<td align="right">179,854,380</td>
<td align="right">0.2%</td>
<td align="right">95.4%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">174,466,263</td>
<td align="right">0.2%</td>
<td align="right">95.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">172,694,470</td>
<td align="right">0.2%</td>
<td align="right">95.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">171,718,416</td>
<td align="right">0.2%</td>
<td align="right">95.9%</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_DICT</td>
<td align="right">162,050,565</td>
<td align="right">0.2%</td>
<td align="right">96.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NONE</td>
<td align="right">157,929,714</td>
<td align="right">0.1%</td>
<td align="right">96.2%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">153,062,317</td>
<td align="right">0.1%</td>
<td align="right">96.3%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_LIST_APPEND</td>
<td align="right">150,444,024</td>
<td align="right">0.1%</td>
<td align="right">96.4%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">144,423,986</td>
<td align="right">0.1%</td>
<td align="right">96.6%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">FOR_ITER_GEN</td>
<td align="right">143,523,422</td>
<td align="right">0.1%</td>
<td align="right">96.7%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">136,177,192</td>
<td align="right">0.1%</td>
<td align="right">96.8%</td>
<td align="right">5.8%</td>
</tr>
<tr>
<td align="left">TO_BOOL_ALWAYS_TRUE</td>
<td align="right">114,224,364</td>
<td align="right">0.1%</td>
<td align="right">96.9%</td>
<td align="right">22.3%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_EXACT_ARGS</td>
<td align="right">109,749,360</td>
<td align="right">0.1%</td>
<td align="right">97.0%</td>
<td align="right">7.7%</td>
</tr>
<tr>
<td align="left">FORMAT_SIMPLE</td>
<td align="right">109,660,320</td>
<td align="right">0.1%</td>
<td align="right">97.1%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_GETITEM</td>
<td align="right">108,343,372</td>
<td align="right">0.1%</td>
<td align="right">97.2%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_SLICE</td>
<td align="right">108,333,300</td>
<td align="right">0.1%</td>
<td align="right">97.3%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CONVERT_VALUE</td>
<td align="right">105,612,540</td>
<td align="right">0.1%</td>
<td align="right">97.4%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BUILD_SLICE</td>
<td align="right">104,315,100</td>
<td align="right">0.1%</td>
<td align="right">97.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">103,952,536</td>
<td align="right">0.1%</td>
<td align="right">97.6%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">101,407,662</td>
<td align="right">0.1%</td>
<td align="right">97.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">SEND</td>
<td align="right">100,436,900</td>
<td align="right">0.1%</td>
<td align="right">97.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">GET_ANEXT</td>
<td align="right">100,136,760</td>
<td align="right">0.1%</td>
<td align="right">97.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">99,716,537</td>
<td align="right">0.1%</td>
<td align="right">98.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BINARY_SLICE</td>
<td align="right">99,085,080</td>
<td align="right">0.1%</td>
<td align="right">98.1%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LIST_APPEND</td>
<td align="right">81,426,710</td>
<td align="right">0.1%</td>
<td align="right">98.2%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">79,720,562</td>
<td align="right">0.1%</td>
<td align="right">98.3%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS</td>
<td align="right">76,421,320</td>
<td align="right">0.1%</td>
<td align="right">98.3%</td>
<td align="right">2.3%</td>
</tr>
<tr>
<td align="left">DELETE_SUBSCR</td>
<td align="right">73,957,800</td>
<td align="right">0.1%</td>
<td align="right">98.4%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">MAKE_FUNCTION</td>
<td align="right">71,470,213</td>
<td align="right">0.1%</td>
<td align="right">98.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">70,618,376</td>
<td align="right">0.1%</td>
<td align="right">98.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">COMPARE_OP_FLOAT</td>
<td align="right">65,637,134</td>
<td align="right">0.1%</td>
<td align="right">98.6%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">SET_FUNCTION_ATTRIBUTE</td>
<td align="right">64,574,336</td>
<td align="right">0.1%</td>
<td align="right">98.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">TO_BOOL_LIST</td>
<td align="right">64,014,715</td>
<td align="right">0.1%</td>
<td align="right">98.7%</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_NO_DICT</td>
<td align="right">63,898,077</td>
<td align="right">0.1%</td>
<td align="right">98.8%</td>
<td align="right">19.5%</td>
</tr>
<tr>
<td align="left">CALL_ALLOC_AND_ENTER_INIT</td>
<td align="right">60,915,058</td>
<td align="right">0.1%</td>
<td align="right">98.8%</td>
<td align="right">2.8%</td>
</tr>
<tr>
<td align="left">EXIT_INIT_CHECK</td>
<td align="right">59,209,078</td>
<td align="right">0.1%</td>
<td align="right">98.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">TO_BOOL_STR</td>
<td align="right">58,317,400</td>
<td align="right">0.1%</td>
<td align="right">98.9%</td>
<td align="right">4.1%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">58,275,804</td>
<td align="right">0.1%</td>
<td align="right">99.0%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">GET_AWAITABLE</td>
<td align="right">58,268,220</td>
<td align="right">0.1%</td>
<td align="right">99.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_LAZY_DICT</td>
<td align="right">55,783,020</td>
<td align="right">0.1%</td>
<td align="right">99.1%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BUILD_STRING</td>
<td align="right">55,210,440</td>
<td align="right">0.1%</td>
<td align="right">99.1%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_UNICODE</td>
<td align="right">54,559,180</td>
<td align="right">0.1%</td>
<td align="right">99.2%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_ATTR_WITH_HINT</td>
<td align="right">52,470,720</td>
<td align="right">0.0%</td>
<td align="right">99.2%</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_PROPERTY</td>
<td align="right">50,216,996</td>
<td align="right">0.0%</td>
<td align="right">99.3%</td>
<td align="right">21.3%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">49,364,409</td>
<td align="right">0.0%</td>
<td align="right">99.3%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">45,257,606</td>
<td align="right">0.0%</td>
<td align="right">99.4%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_STR_1</td>
<td align="right">44,884,300</td>
<td align="right">0.0%</td>
<td align="right">99.4%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_STR_INT</td>
<td align="right">40,636,920</td>
<td align="right">0.0%</td>
<td align="right">99.5%</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">END_FOR</td>
<td align="right">38,105,807</td>
<td align="right">0.0%</td>
<td align="right">99.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR_METHOD</td>
<td align="right">35,824,588</td>
<td align="right">0.0%</td>
<td align="right">99.5%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_FAST_AND_CLEAR</td>
<td align="right">33,344,156</td>
<td align="right">0.0%</td>
<td align="right">99.6%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_KW_PY</td>
<td align="right">31,711,618</td>
<td align="right">0.0%</td>
<td align="right">99.6%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">30,718,946</td>
<td align="right">0.0%</td>
<td align="right">99.6%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">UNARY_NEGATIVE</td>
<td align="right">29,957,270</td>
<td align="right">0.0%</td>
<td align="right">99.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">INSTRUMENTED_LINE</td>
<td align="right">29,136,120</td>
<td align="right">0.0%</td>
<td align="right">99.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_KW_NON_PY</td>
<td align="right">29,056,255</td>
<td align="right">0.0%</td>
<td align="right">99.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">GET_YIELD_FROM_ITER</td>
<td align="right">27,465,684</td>
<td align="right">0.0%</td>
<td align="right">99.7%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">26,583,218</td>
<td align="right">0.0%</td>
<td align="right">99.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">DICT_MERGE</td>
<td align="right">24,832,599</td>
<td align="right">0.0%</td>
<td align="right">99.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_ATTR_CLASS_WITH_METACLASS_CHECK</td>
<td align="right">15,696,000</td>
<td align="right">0.0%</td>
<td align="right">99.8%</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">MAP_ADD</td>
<td align="right">14,621,908</td>
<td align="right">0.0%</td>
<td align="right">99.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">INSTRUMENTED_RESUME</td>
<td align="right">14,567,820</td>
<td align="right">0.0%</td>
<td align="right">99.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">INSTRUMENTED_RETURN_VALUE</td>
<td align="right">14,567,400</td>
<td align="right">0.0%</td>
<td align="right">99.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_SPECIAL</td>
<td align="right">13,068,456</td>
<td align="right">0.0%</td>
<td align="right">99.8%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">12,728,632</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">POP_EXCEPT</td>
<td align="right">12,413,040</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">PUSH_EXC_INFO</td>
<td align="right">12,413,040</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CHECK_EXC_MATCH</td>
<td align="right">12,052,860</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">UNARY_INVERT</td>
<td align="right">10,961,691</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_TUPLE_1</td>
<td align="right">10,876,487</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">10,733,567</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_NAME</td>
<td align="right">9,003,000</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LIST_EXTEND</td>
<td align="right">8,286,548</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">STORE_ATTR_WITH_HINT</td>
<td align="right">7,614,480</td>
<td align="right">0.0%</td>
<td align="right">99.9%</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_GENERAL</td>
<td align="right">7,413,353</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">7,319,301</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">IMPORT_FROM</td>
<td align="right">6,490,755</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">STORE_GLOBAL</td>
<td align="right">6,151,680</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">IMPORT_NAME</td>
<td align="right">6,014,265</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">END_ASYNC_FOR</td>
<td align="right">6,000,000</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">GET_AITER</td>
<td align="right">6,000,000</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_FAST_CHECK</td>
<td align="right">3,492,324</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BINARY_OP_INPLACE_ADD_UNICODE</td>
<td align="right">2,420,560</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_KW_BOUND_METHOD</td>
<td align="right">1,440,360</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">RERAISE</td>
<td align="right">1,428,420</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">RAISE_VARARGS</td>
<td align="right">1,314,310</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">DELETE_FAST</td>
<td align="right">1,029,420</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR_ATTR</td>
<td align="right">926,821</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">UNPACK_EX</td>
<td align="right">500,280</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE</td>
<td align="right">104,320</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">BUILD_SET</td>
<td align="right">79,637</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">DELETE_ATTR</td>
<td align="right">72,420</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">SET_ADD</td>
<td align="right">26,940</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">DICT_UPDATE</td>
<td align="right">13,140</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">STORE_NAME</td>
<td align="right">11,220</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">WITH_EXCEPT_START</td>
<td align="right">4,080</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_LOCALS</td>
<td align="right">2,700</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CALL_KW</td>
<td align="right">1,904</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_FROM_DICT_OR_DEREF</td>
<td align="right">1,380</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_BUILD_CLASS</td>
<td align="right">1,320</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">CLEANUP_THROW</td>
<td align="right">480</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR</td>
<td align="right">160</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">SET_UPDATE</td>
<td align="right">120</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">INSTRUMENTED_JUMP_BACKWARD</td>
<td align="right">60</td>
<td align="right">0.0%</td>
<td align="right">100.0%</td>
<td align="right"></td>
</tr>
</tbody>
</table>


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 opcode pairs </summary>


Pairs of specialized operations that deoptimize and are then followed by
the corresponding unspecialized instruction are not counted as pairs.

<table>
<thead>
<tr>
<th align="left">Pair</th>
<th align="right">Count</th>
<th align="right">Self</th>
<th align="right">Cumulative</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST LOAD_FAST</td>
<td align="right">3,115,180,484</td>
<td align="right">2.9%</td>
<td align="right">2.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">2,983,095,508</td>
<td align="right">2.8%</td>
<td align="right">5.7%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE LOAD_FAST</td>
<td align="right">2,510,903,187</td>
<td align="right">2.3%</td>
<td align="right">8.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN LOAD_FAST</td>
<td align="right">2,214,472,866</td>
<td align="right">2.1%</td>
<td align="right">10.1%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS RESUME_CHECK</td>
<td align="right">1,678,711,289</td>
<td align="right">1.6%</td>
<td align="right">11.7%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL POP_JUMP_IF_FALSE</td>
<td align="right">1,656,448,842</td>
<td align="right">1.5%</td>
<td align="right">13.2%</td>
</tr>
<tr>
<td align="left">STORE_FAST_STORE_FAST STORE_FAST_STORE_FAST</td>
<td align="right">1,603,172,151</td>
<td align="right">1.5%</td>
<td align="right">14.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_SMALL_INT</td>
<td align="right">1,435,072,821</td>
<td align="right">1.3%</td>
<td align="right">16.0%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK LOAD_FAST</td>
<td align="right">1,429,055,295</td>
<td align="right">1.3%</td>
<td align="right">17.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">1,365,841,714</td>
<td align="right">1.3%</td>
<td align="right">18.7%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT POP_JUMP_IF_FALSE</td>
<td align="right">1,072,602,673</td>
<td align="right">1.0%</td>
<td align="right">19.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE LOAD_FAST</td>
<td align="right">1,070,245,351</td>
<td align="right">1.0%</td>
<td align="right">20.7%</td>
</tr>
<tr>
<td align="left">STORE_FAST LOAD_FAST_LOAD_FAST</td>
<td align="right">899,792,376</td>
<td align="right">0.8%</td>
<td align="right">21.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_GLOBAL_BUILTIN</td>
<td align="right">892,660,741</td>
<td align="right">0.8%</td>
<td align="right">22.3%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD FOR_ITER_LIST</td>
<td align="right">837,343,598</td>
<td align="right">0.8%</td>
<td align="right">23.1%</td>
</tr>
<tr>
<td align="left">CACHE RESUME_CHECK</td>
<td align="right">823,262,076</td>
<td align="right">0.8%</td>
<td align="right">23.9%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL RETURN_VALUE</td>
<td align="right">819,497,895</td>
<td align="right">0.8%</td>
<td align="right">24.6%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN</td>
<td align="right">806,182,676</td>
<td align="right">0.8%</td>
<td align="right">25.4%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT BINARY_OP_ADD_INT</td>
<td align="right">775,488,073</td>
<td align="right">0.7%</td>
<td align="right">26.1%</td>
</tr>
<tr>
<td align="left">POP_TOP JUMP_BACKWARD</td>
<td align="right">767,466,892</td>
<td align="right">0.7%</td>
<td align="right">26.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_GLOBAL_MODULE</td>
<td align="right">723,105,793</td>
<td align="right">0.7%</td>
<td align="right">27.5%</td>
</tr>
<tr>
<td align="left">STORE_FAST STORE_FAST</td>
<td align="right">711,644,638</td>
<td align="right">0.7%</td>
<td align="right">28.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST</td>
<td align="right">675,325,395</td>
<td align="right">0.6%</td>
<td align="right">28.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST CALL_PY_EXACT_ARGS</td>
<td align="right">670,694,939</td>
<td align="right">0.6%</td>
<td align="right">29.4%</td>
</tr>
<tr>
<td align="left">POP_TOP LOAD_FAST</td>
<td align="right">667,499,666</td>
<td align="right">0.6%</td>
<td align="right">30.0%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK LOAD_GLOBAL_BUILTIN</td>
<td align="right">659,929,206</td>
<td align="right">0.6%</td>
<td align="right">30.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST TO_BOOL_BOOL</td>
<td align="right">654,140,963</td>
<td align="right">0.6%</td>
<td align="right">31.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_CONST_IMMORTAL</td>
<td align="right">619,444,694</td>
<td align="right">0.6%</td>
<td align="right">31.9%</td>
</tr>
<tr>
<td align="left">STORE_FAST_STORE_FAST LOAD_FAST</td>
<td align="right">614,644,865</td>
<td align="right">0.6%</td>
<td align="right">32.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST PUSH_NULL</td>
<td align="right">613,378,450</td>
<td align="right">0.6%</td>
<td align="right">33.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL POP_JUMP_IF_TRUE</td>
<td align="right">590,053,629</td>
<td align="right">0.6%</td>
<td align="right">33.5%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK POP_TOP</td>
<td align="right">562,680,691</td>
<td align="right">0.5%</td>
<td align="right">34.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST BINARY_OP_MULTIPLY_FLOAT</td>
<td align="right">560,603,320</td>
<td align="right">0.5%</td>
<td align="right">34.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_ATTR_SLOT</td>
<td align="right">558,487,493</td>
<td align="right">0.5%</td>
<td align="right">35.1%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST STORE_FAST</td>
<td align="right">554,992,487</td>
<td align="right">0.5%</td>
<td align="right">35.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST CALL_BUILTIN_O</td>
<td align="right">538,102,865</td>
<td align="right">0.5%</td>
<td align="right">36.1%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE INTERPRETER_EXIT</td>
<td align="right">534,829,080</td>
<td align="right">0.5%</td>
<td align="right">36.6%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL LOAD_CONST_IMMORTAL</td>
<td align="right">529,232,706</td>
<td align="right">0.5%</td>
<td align="right">37.1%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT COMPARE_OP_INT</td>
<td align="right">516,803,782</td>
<td align="right">0.5%</td>
<td align="right">37.6%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR LOAD_FAST</td>
<td align="right">493,786,337</td>
<td align="right">0.5%</td>
<td align="right">38.1%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST TO_BOOL_BOOL</td>
<td align="right">486,859,720</td>
<td align="right">0.5%</td>
<td align="right">38.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST LOAD_FAST</td>
<td align="right">483,424,847</td>
<td align="right">0.5%</td>
<td align="right">39.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS</td>
<td align="right">476,626,954</td>
<td align="right">0.4%</td>
<td align="right">39.4%</td>
</tr>
<tr>
<td align="left">STORE_FAST LOAD_GLOBAL_BUILTIN</td>
<td align="right">474,454,465</td>
<td align="right">0.4%</td>
<td align="right">39.9%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE INTERPRETER_EXIT</td>
<td align="right">462,589,122</td>
<td align="right">0.4%</td>
<td align="right">40.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_ATTR</td>
<td align="right">457,925,491</td>
<td align="right">0.4%</td>
<td align="right">40.7%</td>
</tr>
<tr>
<td align="left">PUSH_NULL LOAD_FAST</td>
<td align="right">455,945,934</td>
<td align="right">0.4%</td>
<td align="right">41.1%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST</td>
<td align="right">455,251,153</td>
<td align="right">0.4%</td>
<td align="right">41.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">451,888,752</td>
<td align="right">0.4%</td>
<td align="right">42.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST RETURN_VALUE</td>
<td align="right">449,244,925</td>
<td align="right">0.4%</td>
<td align="right">42.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST</td>
<td align="right">449,159,875</td>
<td align="right">0.4%</td>
<td align="right">42.8%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE JUMP_BACKWARD</td>
<td align="right">435,177,477</td>
<td align="right">0.4%</td>
<td align="right">43.2%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN CALL_BUILTIN_FAST</td>
<td align="right">434,497,240</td>
<td align="right">0.4%</td>
<td align="right">43.6%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE LOAD_FAST</td>
<td align="right">431,719,440</td>
<td align="right">0.4%</td>
<td align="right">44.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST</td>
<td align="right">423,732,770</td>
<td align="right">0.4%</td>
<td align="right">44.4%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF LOAD_FAST</td>
<td align="right">421,191,708</td>
<td align="right">0.4%</td>
<td align="right">44.8%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE POP_TOP</td>
<td align="right">418,941,886</td>
<td align="right">0.4%</td>
<td align="right">45.2%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE RETURN_VALUE</td>
<td align="right">418,761,752</td>
<td align="right">0.4%</td>
<td align="right">45.6%</td>
</tr>
<tr>
<td align="left">STORE_FAST JUMP_BACKWARD</td>
<td align="right">416,247,162</td>
<td align="right">0.4%</td>
<td align="right">46.0%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD FOR_ITER_RANGE</td>
<td align="right">411,642,200</td>
<td align="right">0.4%</td>
<td align="right">46.4%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE LOAD_FAST</td>
<td align="right">408,979,464</td>
<td align="right">0.4%</td>
<td align="right">46.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST LOAD_FAST</td>
<td align="right">405,322,768</td>
<td align="right">0.4%</td>
<td align="right">47.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE TO_BOOL_BOOL</td>
<td align="right">400,358,471</td>
<td align="right">0.4%</td>
<td align="right">47.5%</td>
</tr>
<tr>
<td align="left">FOR_ITER_RANGE STORE_FAST</td>
<td align="right">395,933,000</td>
<td align="right">0.4%</td>
<td align="right">47.9%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE TO_BOOL_BOOL</td>
<td align="right">392,171,827</td>
<td align="right">0.4%</td>
<td align="right">48.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT LOAD_FAST</td>
<td align="right">387,006,773</td>
<td align="right">0.4%</td>
<td align="right">48.6%</td>
</tr>
<tr>
<td align="left">IS_OP POP_JUMP_IF_FALSE</td>
<td align="right">385,438,548</td>
<td align="right">0.4%</td>
<td align="right">49.0%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O POP_TOP</td>
<td align="right">379,849,320</td>
<td align="right">0.4%</td>
<td align="right">49.3%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK JUMP_BACKWARD_NO_INTERRUPT</td>
<td align="right">373,516,200</td>
<td align="right">0.3%</td>
<td align="right">49.7%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE YIELD_VALUE</td>
<td align="right">373,392,444</td>
<td align="right">0.3%</td>
<td align="right">50.0%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_NO_INTERRUPT SEND_GEN</td>
<td align="right">373,377,860</td>
<td align="right">0.3%</td>
<td align="right">50.4%</td>
</tr>
<tr>
<td align="left">SEND_GEN RESUME_CHECK</td>
<td align="right">373,371,480</td>
<td align="right">0.3%</td>
<td align="right">50.7%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_SET POP_JUMP_IF_FALSE</td>
<td align="right">359,112,331</td>
<td align="right">0.3%</td>
<td align="right">51.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST BINARY_SUBSCR</td>
<td align="right">354,189,015</td>
<td align="right">0.3%</td>
<td align="right">51.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST CALL_TYPE_1</td>
<td align="right">352,080,855</td>
<td align="right">0.3%</td>
<td align="right">51.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_FLOAT BINARY_OP_ADD_FLOAT</td>
<td align="right">349,743,300</td>
<td align="right">0.3%</td>
<td align="right">52.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST BINARY_SUBSCR</td>
<td align="right">348,647,169</td>
<td align="right">0.3%</td>
<td align="right">52.4%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT BINARY_OP_SUBTRACT_INT</td>
<td align="right">347,665,098</td>
<td align="right">0.3%</td>
<td align="right">52.7%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE LOAD_FAST</td>
<td align="right">342,607,891</td>
<td align="right">0.3%</td>
<td align="right">53.0%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE RETURN_VALUE</td>
<td align="right">334,691,644</td>
<td align="right">0.3%</td>
<td align="right">53.3%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST</td>
<td align="right">332,090,356</td>
<td align="right">0.3%</td>
<td align="right">53.6%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE STORE_FAST</td>
<td align="right">331,185,953</td>
<td align="right">0.3%</td>
<td align="right">53.9%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST STORE_FAST</td>
<td align="right">322,305,212</td>
<td align="right">0.3%</td>
<td align="right">54.2%</td>
</tr>
<tr>
<td align="left">CALL_TYPE_1 STORE_FAST</td>
<td align="right">322,246,047</td>
<td align="right">0.3%</td>
<td align="right">54.6%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE CONTAINS_OP_SET</td>
<td align="right">321,138,480</td>
<td align="right">0.3%</td>
<td align="right">54.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">320,847,383</td>
<td align="right">0.3%</td>
<td align="right">55.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST LOAD_DEREF</td>
<td align="right">317,029,201</td>
<td align="right">0.3%</td>
<td align="right">55.4%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL LOAD_FAST</td>
<td align="right">314,023,626</td>
<td align="right">0.3%</td>
<td align="right">55.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">289,709,621</td>
<td align="right">0.3%</td>
<td align="right">56.0%</td>
</tr>
<tr>
<td align="left">NOP LOAD_FAST</td>
<td align="right">285,074,539</td>
<td align="right">0.3%</td>
<td align="right">56.3%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">285,029,002</td>
<td align="right">0.3%</td>
<td align="right">56.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">284,928,264</td>
<td align="right">0.3%</td>
<td align="right">56.8%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT STORE_FAST</td>
<td align="right">284,730,926</td>
<td align="right">0.3%</td>
<td align="right">57.1%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT BINARY_OP</td>
<td align="right">283,831,101</td>
<td align="right">0.3%</td>
<td align="right">57.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS</td>
<td align="right">283,497,686</td>
<td align="right">0.3%</td>
<td align="right">57.6%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL CALL_BUILTIN_FAST</td>
<td align="right">280,321,989</td>
<td align="right">0.3%</td>
<td align="right">57.9%</td>
</tr>
<tr>
<td align="left">SWAP SWAP</td>
<td align="right">276,963,222</td>
<td align="right">0.3%</td>
<td align="right">58.1%</td>
</tr>
<tr>
<td align="left">COPY COPY</td>
<td align="right">269,772,840</td>
<td align="right">0.3%</td>
<td align="right">58.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST BINARY_OP_ADD_INT</td>
<td align="right">258,521,760</td>
<td align="right">0.2%</td>
<td align="right">58.6%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD FOR_ITER</td>
<td align="right">256,709,723</td>
<td align="right">0.2%</td>
<td align="right">58.9%</td>
</tr>
</tbody>
</table>


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each Tier 1 opcode. </summary>


This does not include the unspecialized instructions that occur after a
specialized instruction deoptimizes.

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">36,543,780</td>
<td align="right">36.9%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">31,039,180</td>
<td align="right">31.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">25,745,180</td>
<td align="right">26.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">4,782,720</td>
<td align="right">4.8%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">544,920</td>
<td align="right">0.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">25,395,840</td>
<td align="right">25.6%</td>
</tr>
<tr>
<td align="left">CALL_LIST_APPEND</td>
<td align="right">19,300,980</td>
<td align="right">19.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">15,301,800</td>
<td align="right">15.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">10,123,060</td>
<td align="right">10.2%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">9,047,340</td>
<td align="right">9.1%</td>
</tr>
</tbody>
</table>


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">103,909,800</td>
<td align="right">95.9%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">4,157,100</td>
<td align="right">3.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">258,360</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">8,040</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">103,874,700</td>
<td align="right">95.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">4,156,860</td>
<td align="right">3.8%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">267,000</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">34,380</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">120</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">823,262,076</td>
<td align="right">79.9%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">74,242,288</td>
<td align="right">7.2%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">58,273,021</td>
<td align="right">5.7%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">42,467,652</td>
<td align="right">4.1%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">30,362,460</td>
<td align="right">2.9%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">354,189,015</td>
<td align="right">29.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">348,647,169</td>
<td align="right">28.6%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">109,352,700</td>
<td align="right">9.0%</td>
</tr>
<tr>
<td align="left">BUILD_SLICE</td>
<td align="right">103,874,760</td>
<td align="right">8.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">103,604,000</td>
<td align="right">8.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">493,786,337</td>
<td align="right">40.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">171,085,380</td>
<td align="right">14.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_FLOAT</td>
<td align="right">115,701,000</td>
<td align="right">9.5%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">111,400,759</td>
<td align="right">9.1%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">96,307,204</td>
<td align="right">7.9%</td>
</tr>
</tbody>
</table>


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">11,110,528</td>
<td align="right">92.2%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">486,910</td>
<td align="right">4.0%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">428,420</td>
<td align="right">3.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">25,800</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,200</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">12,052,740</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">120</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">59,209,078</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">59,209,078</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">221,970,139</td>
<td align="right">42.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">61,814,580</td>
<td align="right">11.8%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">55,556,382</td>
<td align="right">10.6%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">43,280,843</td>
<td align="right">8.3%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">37,735,080</td>
<td align="right">7.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">217,972,076</td>
<td align="right">41.6%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">75,193,659</td>
<td align="right">14.3%</td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">70,116,582</td>
<td align="right">13.4%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">66,834,238</td>
<td align="right">12.7%</td>
</tr>
<tr>
<td align="left">FOR_ITER_GEN</td>
<td align="right">37,817,888</td>
<td align="right">7.2%</td>
</tr>
</tbody>
</table>


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">534,829,080</td>
<td align="right">52.0%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">462,589,122</td>
<td align="right">45.0%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">30,362,700</td>
<td align="right">3.0%</td>
</tr>
</tbody>
</table>


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">71,470,213</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">SET_FUNCTION_ATTRIBUTE</td>
<td align="right">64,570,256</td>
<td align="right">90.3%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">2,498,700</td>
<td align="right">3.5%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">1,949,506</td>
<td align="right">2.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,522,739</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">696,510</td>
<td align="right">1.0%</td>
</tr>
</tbody>
</table>


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">130,706,348</td>
<td align="right">33.7%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">54,967,058</td>
<td align="right">14.2%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">53,990,267</td>
<td align="right">13.9%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">51,310,320</td>
<td align="right">13.2%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">24,907,920</td>
<td align="right">6.4%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">285,074,539</td>
<td align="right">73.6%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">29,627,178</td>
<td align="right">7.6%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">17,271,900</td>
<td align="right">4.5%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">15,995,493</td>
<td align="right">4.1%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">14,067,580</td>
<td align="right">3.6%</td>
</tr>
</tbody>
</table>


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_TOP</td>
<td align="right">6,309,294</td>
<td align="right">50.8%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_DICT</td>
<td align="right">3,189,120</td>
<td align="right">25.7%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">1,274,607</td>
<td align="right">10.3%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">932,040</td>
<td align="right">7.5%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">529,899</td>
<td align="right">4.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">7,284,264</td>
<td align="right">58.7%</td>
</tr>
<tr>
<td align="left">JUMP_FORWARD</td>
<td align="right">2,026,380</td>
<td align="right">16.3%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">1,217,007</td>
<td align="right">9.8%</td>
</tr>
<tr>
<td align="left">RERAISE</td>
<td align="right">932,040</td>
<td align="right">7.5%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">707,270</td>
<td align="right">5.7%</td>
</tr>
</tbody>
</table>


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">562,680,691</td>
<td align="right">28.3%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">418,941,886</td>
<td align="right">21.0%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">379,849,320</td>
<td align="right">19.1%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">134,448,738</td>
<td align="right">6.8%</td>
</tr>
<tr>
<td align="left">SEND_GEN</td>
<td align="right">85,591,144</td>
<td align="right">4.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">767,466,892</td>
<td align="right">38.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">667,499,666</td>
<td align="right">33.5%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">198,022,620</td>
<td align="right">9.9%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">125,462,182</td>
<td align="right">6.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">78,937,383</td>
<td align="right">4.0%</td>
</tr>
</tbody>
</table>


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_SUBSCR_DICT</td>
<td align="right">5,373,480</td>
<td align="right">43.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_PROPERTY</td>
<td align="right">3,258,540</td>
<td align="right">26.3%</td>
</tr>
<tr>
<td align="left">RERAISE</td>
<td align="right">926,760</td>
<td align="right">7.5%</td>
</tr>
<tr>
<td align="left">RAISE_VARARGS</td>
<td align="right">885,430</td>
<td align="right">7.1%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">843,060</td>
<td align="right">6.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">11,195,266</td>
<td align="right">90.2%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">834,290</td>
<td align="right">6.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">379,140</td>
<td align="right">3.1%</td>
</tr>
<tr>
<td align="left">WITH_EXCEPT_START</td>
<td align="right">4,080</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">264</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">613,378,450</td>
<td align="right">67.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">145,016,023</td>
<td align="right">15.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">47,715,872</td>
<td align="right">5.2%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">45,711,001</td>
<td align="right">5.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">22,557,737</td>
<td align="right">2.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">455,945,934</td>
<td align="right">49.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">231,132,072</td>
<td align="right">25.3%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">54,836,154</td>
<td align="right">6.0%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">54,503,220</td>
<td align="right">6.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">29,649,878</td>
<td align="right">3.2%</td>
</tr>
</tbody>
</table>


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">105,229,219</td>
<td align="right">53.1%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">60,901,881</td>
<td align="right">30.8%</td>
</tr>
<tr>
<td align="left">CACHE</td>
<td align="right">30,362,460</td>
<td align="right">15.3%</td>
</tr>
<tr>
<td align="left">CALL_KW_PY</td>
<td align="right">728,640</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">569,820</td>
<td align="right">0.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">GET_AWAITABLE</td>
<td align="right">58,268,220</td>
<td align="right">29.4%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">48,222,060</td>
<td align="right">24.4%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">37,735,080</td>
<td align="right">19.1%</td>
</tr>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">30,362,700</td>
<td align="right">15.3%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">7,425,325</td>
<td align="right">3.7%</td>
</tr>
</tbody>
</table>


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">819,497,895</td>
<td align="right">27.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">449,244,925</td>
<td align="right">15.0%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">418,761,752</td>
<td align="right">13.9%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">334,691,644</td>
<td align="right">11.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">128,874,377</td>
<td align="right">4.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">534,829,080</td>
<td align="right">17.8%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">418,941,886</td>
<td align="right">13.9%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">418,761,752</td>
<td align="right">13.9%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">331,185,953</td>
<td align="right">11.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">240,709,689</td>
<td align="right">8.0%</td>
</tr>
</tbody>
</table>


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">SWAP</td>
<td align="right">109,360,580</td>
<td align="right">35.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">79,719,806</td>
<td align="right">25.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">54,457,700</td>
<td align="right">17.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">41,532,300</td>
<td align="right">13.4%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">9,301,500</td>
<td align="right">3.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">110,750,820</td>
<td align="right">35.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">104,112,960</td>
<td align="right">33.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">28,998,220</td>
<td align="right">9.3%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">27,005,800</td>
<td align="right">8.7%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">15,723,060</td>
<td align="right">5.1%</td>
</tr>
</tbody>
</table>


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">138,398,089</td>
<td align="right">79.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">24,536,900</td>
<td align="right">14.1%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">7,714,880</td>
<td align="right">4.4%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">1,383,100</td>
<td align="right">0.8%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_TUPLE_INT</td>
<td align="right">1,320,120</td>
<td align="right">0.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">118,563,935</td>
<td align="right">68.0%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">55,544,028</td>
<td align="right">31.8%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">195,923</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">61,533</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">54,845</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">14,647,440</td>
<td align="right">48.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">8,002,378</td>
<td align="right">26.7%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">3,041,379</td>
<td align="right">10.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">2,102,223</td>
<td align="right">7.0%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_TUPLE_INT</td>
<td align="right">1,205,640</td>
<td align="right">4.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">16,564,560</td>
<td align="right">55.3%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">3,126,360</td>
<td align="right">10.4%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">2,419,140</td>
<td align="right">8.1%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">2,419,140</td>
<td align="right">8.1%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">1,921,320</td>
<td align="right">6.4%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">283,831,101</td>
<td align="right">29.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">170,202,750</td>
<td align="right">17.6%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">72,001,440</td>
<td align="right">7.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">66,311,459</td>
<td align="right">6.8%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">65,379,206</td>
<td align="right">6.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">174,596,337</td>
<td align="right">18.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">167,749,669</td>
<td align="right">17.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">120,306,500</td>
<td align="right">12.4%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">96,694,080</td>
<td align="right">10.0%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">88,331,313</td>
<td align="right">9.1%</td>
</tr>
</tbody>
</table>


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">102,286,525</td>
<td align="right">55.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">19,633,036</td>
<td align="right">10.6%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">11,528,460</td>
<td align="right">6.2%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">11,216,703</td>
<td align="right">6.1%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">9,776,922</td>
<td align="right">5.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">107,421,532</td>
<td align="right">58.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">36,648,416</td>
<td align="right">19.8%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">9,776,982</td>
<td align="right">5.3%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">8,186,105</td>
<td align="right">4.4%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">8,086,329</td>
<td align="right">4.4%</td>
</tr>
</tbody>
</table>


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">13,977,892</td>
<td align="right">19.8%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">12,076,143</td>
<td align="right">17.1%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">7,992,940</td>
<td align="right">11.3%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">6,481,440</td>
<td align="right">9.2%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">5,463,114</td>
<td align="right">7.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">32,793,098</td>
<td align="right">46.4%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">18,248,936</td>
<td align="right">25.8%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">7,992,940</td>
<td align="right">11.3%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">4,100,160</td>
<td align="right">5.8%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">3,960,360</td>
<td align="right">5.6%</td>
</tr>
</tbody>
</table>


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">176,175,387</td>
<td align="right">30.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">163,506,762</td>
<td align="right">28.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">125,628,294</td>
<td align="right">21.7%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">36,001,200</td>
<td align="right">6.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">16,437,525</td>
<td align="right">2.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">334,691,644</td>
<td align="right">57.9%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">64,730,542</td>
<td align="right">11.2%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">32,211,960</td>
<td align="right">5.6%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_GETITEM</td>
<td align="right">28,812,000</td>
<td align="right">5.0%</td>
</tr>
<tr>
<td align="left">LIST_APPEND</td>
<td align="right">23,077,051</td>
<td align="right">4.0%</td>
</tr>
</tbody>
</table>


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_SUBSCR_TUPLE_INT</td>
<td align="right">72,000,000</td>
<td align="right">90.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">6,209,462</td>
<td align="right">7.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">1,080,320</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">194,794</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">189,804</td>
<td align="right">0.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">36,001,200</td>
<td align="right">45.2%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">36,001,200</td>
<td align="right">45.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">6,000,000</td>
<td align="right">7.5%</td>
</tr>
<tr>
<td align="left">CALL_LIST_APPEND</td>
<td align="right">1,080,040</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">378,060</td>
<td align="right">0.5%</td>
</tr>
</tbody>
</table>


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">DICT_MERGE</td>
<td align="right">24,832,599</td>
<td align="right">54.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">14,293,482</td>
<td align="right">31.6%</td>
</tr>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">5,181,300</td>
<td align="right">11.4%</td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">648,780</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">139,440</td>
<td align="right">0.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">14,144,328</td>
<td align="right">31.3%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">11,454,195</td>
<td align="right">25.3%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">6,595,480</td>
<td align="right">14.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">4,981,620</td>
<td align="right">11.0%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">2,970,281</td>
<td align="right">6.6%</td>
</tr>
</tbody>
</table>


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">88,136,760</td>
<td align="right">86.9%</td>
</tr>
<tr>
<td align="left">LIST_EXTEND</td>
<td align="right">7,258,902</td>
<td align="right">7.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">6,000,000</td>
<td align="right">5.9%</td>
</tr>
<tr>
<td align="left">LIST_APPEND</td>
<td align="right">11,520</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CLEANUP_THROW</td>
<td align="right">480</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">94,136,760</td>
<td align="right">92.8%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">5,181,300</td>
<td align="right">5.1%</td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">1,954,302</td>
<td align="right">1.9%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">133,860</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">UNPACK_EX</td>
<td align="right">960</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">1,904</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_KW_PY</td>
<td align="right">960</td>
<td align="right">50.4%</td>
</tr>
<tr>
<td align="left">CALL_KW_NON_PY</td>
<td align="right">904</td>
<td align="right">47.5%</td>
</tr>
<tr>
<td align="left">CALL_KW_BOUND_METHOD</td>
<td align="right">40</td>
<td align="right">2.1%</td>
</tr>
</tbody>
</table>


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">46,723,706</td>
<td align="right">32.4%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">39,912,844</td>
<td align="right">27.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">16,838,499</td>
<td align="right">11.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">8,841,610</td>
<td align="right">6.1%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">6,868,789</td>
<td align="right">4.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">89,311,285</td>
<td align="right">61.8%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">41,891,622</td>
<td align="right">29.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">4,684,940</td>
<td align="right">3.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">4,684,940</td>
<td align="right">3.2%</td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">2,531,397</td>
<td align="right">1.8%</td>
</tr>
</tbody>
</table>


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">75,092,700</td>
<td align="right">43.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">58,268,820</td>
<td align="right">33.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">19,521,323</td>
<td align="right">11.3%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">5,347,215</td>
<td align="right">3.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">3,443,580</td>
<td align="right">2.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">154,750,498</td>
<td align="right">89.6%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">14,755,200</td>
<td align="right">8.5%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">2,736,900</td>
<td align="right">1.6%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">331,440</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">70,020</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">COPY</td>
<td align="right">269,772,840</td>
<td align="right">28.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">222,091,497</td>
<td align="right">23.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">121,554,720</td>
<td align="right">12.8%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">102,958,020</td>
<td align="right">10.8%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">93,557,940</td>
<td align="right">9.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">COPY</td>
<td align="right">269,772,840</td>
<td align="right">28.4%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">159,175,780</td>
<td align="right">16.7%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">133,097,553</td>
<td align="right">14.0%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">109,352,700</td>
<td align="right">11.5%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">100,011,960</td>
<td align="right">10.5%</td>
</tr>
</tbody>
</table>


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">65,716,974</td>
<td align="right">42.9%</td>
</tr>
<tr>
<td align="left">CACHE</td>
<td align="right">42,467,652</td>
<td align="right">27.7%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_EXACT_ARGS</td>
<td align="right">27,084,413</td>
<td align="right">17.7%</td>
</tr>
<tr>
<td align="left">CALL_PY_GENERAL</td>
<td align="right">8,777,824</td>
<td align="right">5.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_PROPERTY</td>
<td align="right">3,993,374</td>
<td align="right">2.6%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">92,100,856</td>
<td align="right">60.2%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">60,901,881</td>
<td align="right">39.8%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">59,520</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">60</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">85,225,182</td>
<td align="right">27.3%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_STR</td>
<td align="right">73,423,560</td>
<td align="right">23.5%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">56,360,342</td>
<td align="right">18.1%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">20,371,020</td>
<td align="right">6.5%</td>
</tr>
<tr>
<td align="left">IS_OP</td>
<td align="right">18,013,860</td>
<td align="right">5.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">182,395,622</td>
<td align="right">58.4%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">43,376,082</td>
<td align="right">13.9%</td>
</tr>
<tr>
<td align="left">FOR_ITER_GEN</td>
<td align="right">26,083,460</td>
<td align="right">8.4%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">18,018,492</td>
<td align="right">5.8%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">16,303,669</td>
<td align="right">5.2%</td>
</tr>
</tbody>
</table>


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">256,709,723</td>
<td align="right">73.3%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">75,193,659</td>
<td align="right">21.5%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">18,018,492</td>
<td align="right">5.1%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">113,453</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">9,376</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">194,372,956</td>
<td align="right">55.5%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">87,022,154</td>
<td align="right">24.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">24,639,124</td>
<td align="right">7.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">13,264,125</td>
<td align="right">3.8%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">10,501,660</td>
<td align="right">3.0%</td>
</tr>
</tbody>
</table>


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR_CLASS</td>
<td align="right">216,000,120</td>
<td align="right">47.7%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">135,972,542</td>
<td align="right">30.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">45,835,587</td>
<td align="right">10.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">15,682,651</td>
<td align="right">3.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">12,850,634</td>
<td align="right">2.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">385,438,548</td>
<td align="right">85.1%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">35,164,661</td>
<td align="right">7.8%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">18,013,860</td>
<td align="right">4.0%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">9,352,734</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">2,447,260</td>
<td align="right">0.5%</td>
</tr>
</tbody>
</table>


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_TOP</td>
<td align="right">767,466,892</td>
<td align="right">34.7%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">435,177,477</td>
<td align="right">19.7%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">416,247,162</td>
<td align="right">18.8%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">110,750,820</td>
<td align="right">5.0%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_LIST_INT</td>
<td align="right">96,709,864</td>
<td align="right">4.4%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">837,343,598</td>
<td align="right">37.9%</td>
</tr>
<tr>
<td align="left">FOR_ITER_RANGE</td>
<td align="right">411,642,200</td>
<td align="right">18.6%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">256,709,723</td>
<td align="right">11.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">209,066,929</td>
<td align="right">9.5%</td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">183,264,876</td>
<td align="right">8.3%</td>
</tr>
</tbody>
</table>


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">89,656,120</td>
<td align="right">33.8%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">83,514,195</td>
<td align="right">31.5%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">35,781,413</td>
<td align="right">13.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">11,995,080</td>
<td align="right">4.5%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">9,156,969</td>
<td align="right">3.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">121,977,570</td>
<td align="right">46.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">47,674,736</td>
<td align="right">18.0%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">34,686,060</td>
<td align="right">13.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">24,899,059</td>
<td align="right">9.4%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">7,968,300</td>
<td align="right">3.0%</td>
</tr>
</tbody>
</table>


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">24,078,840</td>
<td align="right">29.6%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">23,077,051</td>
<td align="right">28.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">14,499,758</td>
<td align="right">17.8%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">4,800,000</td>
<td align="right">5.9%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">3,971,010</td>
<td align="right">4.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">81,319,190</td>
<td align="right">99.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">96,000</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">11,520</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">7,320,295</td>
<td align="right">88.3%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">694,020</td>
<td align="right">8.4%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">169,213</td>
<td align="right">2.0%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">77,400</td>
<td align="right">0.9%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">19,200</td>
<td align="right">0.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">7,258,902</td>
<td align="right">87.6%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">502,213</td>
<td align="right">6.1%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_LIST</td>
<td align="right">345,120</td>
<td align="right">4.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">176,413</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">2,940</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">457,925,491</td>
<td align="right">70.9%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">78,830,102</td>
<td align="right">12.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">44,104,809</td>
<td align="right">6.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">34,697,269</td>
<td align="right">5.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">15,534,123</td>
<td align="right">2.4%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">221,105,990</td>
<td align="right">34.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">82,132,237</td>
<td align="right">12.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">80,213,480</td>
<td align="right">12.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">34,697,269</td>
<td align="right">5.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">26,546,185</td>
<td align="right">4.1%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">138,615,993</td>
<td align="right">20.2%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">71,488,039</td>
<td align="right">10.4%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">64,730,542</td>
<td align="right">9.4%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">54,945,900</td>
<td align="right">8.0%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">54,836,154</td>
<td align="right">8.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">111,966,534</td>
<td align="right">16.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">72,025,620</td>
<td align="right">10.5%</td>
</tr>
<tr>
<td align="left">MAKE_FUNCTION</td>
<td align="right">71,470,213</td>
<td align="right">10.4%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">59,105,080</td>
<td align="right">8.6%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS</td>
<td align="right">54,958,560</td>
<td align="right">8.0%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">317,029,201</td>
<td align="right">57.6%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">46,765,320</td>
<td align="right">8.5%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">38,343,170</td>
<td align="right">7.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">30,578,431</td>
<td align="right">5.6%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">23,468,820</td>
<td align="right">4.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">421,191,708</td>
<td align="right">76.6%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">45,711,001</td>
<td align="right">8.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">18,260,050</td>
<td align="right">3.3%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_DICT</td>
<td align="right">11,065,080</td>
<td align="right">2.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">6,981,480</td>
<td align="right">1.3%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">3,115,180,484</td>
<td align="right">15.6%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">2,510,903,187</td>
<td align="right">12.6%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">2,214,472,866</td>
<td align="right">11.1%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">1,429,055,295</td>
<td align="right">7.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">1,070,245,351</td>
<td align="right">5.4%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">2,983,095,508</td>
<td align="right">14.9%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">1,435,072,821</td>
<td align="right">7.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">1,365,841,714</td>
<td align="right">6.8%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">892,660,741</td>
<td align="right">4.5%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">723,105,793</td>
<td align="right">3.6%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">GET_ITER</td>
<td align="right">17,787,922</td>
<td align="right">53.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_AND_CLEAR</td>
<td align="right">15,556,234</td>
<td align="right">46.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">SWAP</td>
<td align="right">17,787,922</td>
<td align="right">53.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_AND_CLEAR</td>
<td align="right">15,556,234</td>
<td align="right">46.7%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">1,161,840</td>
<td align="right">33.3%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NONE</td>
<td align="right">1,037,580</td>
<td align="right">29.7%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NOT_NONE</td>
<td align="right">522,771</td>
<td align="right">15.0%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">409,920</td>
<td align="right">11.7%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">221,940</td>
<td align="right">6.4%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_LIST_APPEND</td>
<td align="right">1,161,840</td>
<td align="right">33.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,049,100</td>
<td align="right">30.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">462,971</td>
<td align="right">13.3%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">408,000</td>
<td align="right">11.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">219,580</td>
<td align="right">6.3%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">899,792,376</td>
<td align="right">18.7%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">455,251,153</td>
<td align="right">9.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">449,159,875</td>
<td align="right">9.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">423,732,770</td>
<td align="right">8.8%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">231,132,072</td>
<td align="right">4.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">483,424,847</td>
<td align="right">10.0%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">476,626,954</td>
<td align="right">9.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">449,159,875</td>
<td align="right">9.3%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">354,189,015</td>
<td align="right">7.4%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">320,847,383</td>
<td align="right">6.7%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">INSTRUMENTED_LINE</td>
<td align="right">7,283,700</td>
<td align="right">99.5%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">6,620</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">4,549</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">4,166</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">3,220</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">7,283,982</td>
<td align="right">99.5%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">22,490</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">10,450</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">1,607</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">300</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_SMALL_INT

<details>
<summary> Successors and predecessors for LOAD_SMALL_INT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,435,072,821</td>
<td align="right">48.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">231,307,690</td>
<td align="right">7.8%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">198,595,380</td>
<td align="right">6.7%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">137,327,387</td>
<td align="right">4.6%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">129,507,693</td>
<td align="right">4.4%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">775,488,073</td>
<td align="right">26.2%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">516,803,782</td>
<td align="right">17.4%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_INT</td>
<td align="right">347,665,098</td>
<td align="right">11.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">283,831,101</td>
<td align="right">9.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">223,594,869</td>
<td align="right">7.5%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_SUPER_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">160</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_SUPER_ATTR_METHOD</td>
<td align="right">160</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">4,860,579</td>
<td align="right">38.2%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">2,429,471</td>
<td align="right">19.1%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">2,320,762</td>
<td align="right">18.2%</td>
</tr>
<tr>
<td align="left">CACHE</td>
<td align="right">1,301,725</td>
<td align="right">10.2%</td>
</tr>
<tr>
<td align="left">CALL_PY_GENERAL</td>
<td align="right">949,388</td>
<td align="right">7.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">7,298,233</td>
<td align="right">57.3%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">4,860,579</td>
<td align="right">38.2%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">569,820</td>
<td align="right">4.5%</td>
</tr>
</tbody>
</table>


</details>

### MAP_ADD

<details>
<summary> Successors and predecessors for MAP_ADD </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">6,195,600</td>
<td align="right">42.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">5,844,808</td>
<td align="right">40.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,287,600</td>
<td align="right">8.8%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">1,205,640</td>
<td align="right">8.2%</td>
</tr>
<tr>
<td align="left">JUMP_FORWARD</td>
<td align="right">76,080</td>
<td align="right">0.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">14,570,968</td>
<td align="right">99.7%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">47,940</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">3,000</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">1,656,448,842</td>
<td align="right">34.8%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">1,072,602,673</td>
<td align="right">22.6%</td>
</tr>
<tr>
<td align="left">IS_OP</td>
<td align="right">385,438,548</td>
<td align="right">8.1%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_SET</td>
<td align="right">359,112,331</td>
<td align="right">7.6%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">225,265,780</td>
<td align="right">4.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">2,510,903,187</td>
<td align="right">52.8%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">806,182,676</td>
<td align="right">17.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">455,251,153</td>
<td align="right">9.6%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">243,700,181</td>
<td align="right">5.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">163,498,978</td>
<td align="right">3.4%</td>
</tr>
</tbody>
</table>


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">191,081,129</td>
<td align="right">81.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">22,202,904</td>
<td align="right">9.5%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">8,870,340</td>
<td align="right">3.8%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">7,323,040</td>
<td align="right">3.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">3,790,540</td>
<td align="right">1.6%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">154,151,569</td>
<td align="right">65.9%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">26,609,135</td>
<td align="right">11.4%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">17,475,289</td>
<td align="right">7.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">11,414,799</td>
<td align="right">4.9%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">9,107,090</td>
<td align="right">3.9%</td>
</tr>
</tbody>
</table>


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">590,053,629</td>
<td align="right">50.2%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">118,563,935</td>
<td align="right">10.1%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">107,537,915</td>
<td align="right">9.1%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_DICT</td>
<td align="right">54,683,598</td>
<td align="right">4.6%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">41,891,622</td>
<td align="right">3.6%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">435,177,477</td>
<td align="right">37.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">431,719,440</td>
<td align="right">36.7%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">84,025,807</td>
<td align="right">7.1%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">54,945,900</td>
<td align="right">4.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">34,595,564</td>
<td align="right">2.9%</td>
</tr>
</tbody>
</table>


</details>

### SEND

<details>
<summary> Successors and predecessors for SEND </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">100,273,140</td>
<td align="right">99.8%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_NO_INTERRUPT</td>
<td align="right">138,340</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">SEND</td>
<td align="right">25,180</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">SEND_GEN</td>
<td align="right">240</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">END_SEND</td>
<td align="right">94,269,920</td>
<td align="right">93.9%</td>
</tr>
<tr>
<td align="left">END_ASYNC_FOR</td>
<td align="right">6,000,000</td>
<td align="right">6.0%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">133,660</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">SEND</td>
<td align="right">25,180</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">5,160</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">MAKE_FUNCTION</td>
<td align="right">64,570,256</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">SET_FUNCTION_ATTRIBUTE</td>
<td align="right">4,080</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">60,851,817</td>
<td align="right">94.2%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">2,268,121</td>
<td align="right">3.5%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">705,400</td>
<td align="right">1.1%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">599,400</td>
<td align="right">0.9%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">78,670</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">15,822,660</td>
<td align="right">51.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">6,580,180</td>
<td align="right">21.4%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">5,436,780</td>
<td align="right">17.7%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">1,242,732</td>
<td align="right">4.0%</td>
</tr>
<tr>
<td align="left">CALL_KW_NON_PY</td>
<td align="right">1,200,840</td>
<td align="right">3.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">13,868,012</td>
<td align="right">45.1%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">6,760,080</td>
<td align="right">22.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">6,688,290</td>
<td align="right">21.8%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">2,333,240</td>
<td align="right">7.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">706,150</td>
<td align="right">2.3%</td>
</tr>
</tbody>
</table>


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">3,356,640</td>
<td align="right">31.3%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">2,419,200</td>
<td align="right">22.5%</td>
</tr>
<tr>
<td align="left">FOR_ITER_RANGE</td>
<td align="right">1,658,880</td>
<td align="right">15.5%</td>
</tr>
<tr>
<td align="left">IMPORT_FROM</td>
<td align="right">1,556,531</td>
<td align="right">14.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">1,116,789</td>
<td align="right">10.4%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">4,219,169</td>
<td align="right">39.3%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">3,356,460</td>
<td align="right">31.3%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">1,420,352</td>
<td align="right">13.2%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">1,118,088</td>
<td align="right">10.4%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">357,000</td>
<td align="right">3.3%</td>
</tr>
</tbody>
</table>


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">711,644,638</td>
<td align="right">10.7%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">554,992,487</td>
<td align="right">8.4%</td>
</tr>
<tr>
<td align="left">FOR_ITER_RANGE</td>
<td align="right">395,933,000</td>
<td align="right">6.0%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">331,185,953</td>
<td align="right">5.0%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">322,305,212</td>
<td align="right">4.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">3,115,180,484</td>
<td align="right">47.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">899,792,376</td>
<td align="right">13.6%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">711,644,638</td>
<td align="right">10.7%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">474,454,465</td>
<td align="right">7.2%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">416,247,162</td>
<td align="right">6.3%</td>
</tr>
</tbody>
</table>


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">FOR_ITER_RANGE</td>
<td align="right">21,849,780</td>
<td align="right">44.3%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">19,791,550</td>
<td align="right">40.1%</td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">4,147,679</td>
<td align="right">8.4%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">2,446,680</td>
<td align="right">5.0%</td>
</tr>
<tr>
<td align="left">CALL_LEN</td>
<td align="right">1,084,260</td>
<td align="right">2.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">21,955,278</td>
<td align="right">44.5%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NOT_NONE</td>
<td align="right">8,870,340</td>
<td align="right">18.0%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">4,086,720</td>
<td align="right">8.3%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">3,529,500</td>
<td align="right">7.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">2,354,150</td>
<td align="right">4.8%</td>
</tr>
</tbody>
</table>


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">1,603,172,151</td>
<td align="right">64.3%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">332,090,356</td>
<td align="right">13.3%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">255,856,800</td>
<td align="right">10.3%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_LIST</td>
<td align="right">222,240,969</td>
<td align="right">8.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">45,905,880</td>
<td align="right">1.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">1,603,172,151</td>
<td align="right">64.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">614,644,865</td>
<td align="right">24.7%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">103,024,809</td>
<td align="right">4.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">74,673,639</td>
<td align="right">3.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">46,058,040</td>
<td align="right">1.8%</td>
</tr>
</tbody>
</table>


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">SWAP</td>
<td align="right">276,963,222</td>
<td align="right">32.4%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_FLOAT</td>
<td align="right">116,640,000</td>
<td align="right">13.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">85,741,062</td>
<td align="right">10.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">74,552,572</td>
<td align="right">8.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_INT</td>
<td align="right">67,527,780</td>
<td align="right">7.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">SWAP</td>
<td align="right">276,963,222</td>
<td align="right">32.4%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_LIST_INT</td>
<td align="right">159,175,780</td>
<td align="right">18.6%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">109,360,580</td>
<td align="right">12.8%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">102,958,020</td>
<td align="right">12.0%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">76,960,660</td>
<td align="right">9.0%</td>
</tr>
</tbody>
</table>


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">96,060</td>
<td align="right">92.1%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">2,440</td>
<td align="right">2.3%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">1,540</td>
<td align="right">1.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,351</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">1,042</td>
<td align="right">1.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">96,540</td>
<td align="right">92.5%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">4,298</td>
<td align="right">4.1%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">2,020</td>
<td align="right">1.9%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">620</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE</td>
<td align="right">382</td>
<td align="right">0.4%</td>
</tr>
</tbody>
</table>


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">373,392,444</td>
<td align="right">39.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_FLOAT</td>
<td align="right">210,931,680</td>
<td align="right">22.4%</td>
</tr>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">94,136,760</td>
<td align="right">10.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">69,473,842</td>
<td align="right">7.4%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">32,211,960</td>
<td align="right">3.4%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">INTERPRETER_EXIT</td>
<td align="right">462,589,122</td>
<td align="right">49.1%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">373,392,444</td>
<td align="right">39.7%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">76,365,855</td>
<td align="right">8.1%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">24,808,480</td>
<td align="right">2.6%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">2,419,200</td>
<td align="right">0.3%</td>
</tr>
</tbody>
</table>


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CACHE</td>
<td align="right">58,273,021</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">2,055</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_RESUME</td>
<td align="right">300</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_EXACT_ARGS</td>
<td align="right">240</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">60</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">58,269,560</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">3,428</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,387</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">480</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_NAME</td>
<td align="right">360</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP_MULTIPLY_FLOAT</td>
<td align="right">349,743,300</td>
<td align="right">76.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">61,832,109</td>
<td align="right">13.6%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">17,287,200</td>
<td align="right">3.8%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_INT</td>
<td align="right">8,437,640</td>
<td align="right">1.9%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">7,903,858</td>
<td align="right">1.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">163,601,786</td>
<td align="right">35.9%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">116,640,000</td>
<td align="right">25.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">65,213,400</td>
<td align="right">14.3%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">31,350,960</td>
<td align="right">6.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">29,370,480</td>
<td align="right">6.5%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">775,488,073</td>
<td align="right">62.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">258,521,760</td>
<td align="right">20.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">94,436,051</td>
<td align="right">7.6%</td>
</tr>
<tr>
<td align="left">END_SEND</td>
<td align="right">29,134,080</td>
<td align="right">2.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">25,629,760</td>
<td align="right">2.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">284,730,926</td>
<td align="right">23.1%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">129,507,693</td>
<td align="right">10.5%</td>
</tr>
<tr>
<td align="left">STORE_SLICE</td>
<td align="right">103,909,800</td>
<td align="right">8.4%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">103,604,000</td>
<td align="right">8.4%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_INT</td>
<td align="right">96,238,980</td>
<td align="right">7.8%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">560,603,320</td>
<td align="right">60.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">119,363,280</td>
<td align="right">12.9%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">115,701,000</td>
<td align="right">12.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">71,527,020</td>
<td align="right">7.8%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">24,782,880</td>
<td align="right">2.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP_ADD_FLOAT</td>
<td align="right">349,743,300</td>
<td align="right">37.9%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">210,931,680</td>
<td align="right">22.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">122,666,580</td>
<td align="right">13.3%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_FLOAT</td>
<td align="right">109,285,680</td>
<td align="right">11.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">41,721,880</td>
<td align="right">4.5%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">96,238,980</td>
<td align="right">35.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">50,750,400</td>
<td align="right">18.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">44,982,593</td>
<td align="right">16.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">40,220,980</td>
<td align="right">14.9%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">27,332,760</td>
<td align="right">10.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">62,726,040</td>
<td align="right">23.2%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">62,292,693</td>
<td align="right">23.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">47,483,700</td>
<td align="right">17.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">28,380,780</td>
<td align="right">10.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">24,711,660</td>
<td align="right">9.2%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP_MULTIPLY_FLOAT</td>
<td align="right">109,285,680</td>
<td align="right">38.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">69,337,660</td>
<td align="right">24.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">36,003,600</td>
<td align="right">12.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">29,852,940</td>
<td align="right">10.6%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">24,729,600</td>
<td align="right">8.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">108,668,931</td>
<td align="right">38.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">73,280,400</td>
<td align="right">26.0%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">55,701,000</td>
<td align="right">19.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">29,539,920</td>
<td align="right">10.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_FLOAT</td>
<td align="right">10,737,420</td>
<td align="right">3.8%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">347,665,098</td>
<td align="right">72.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">69,798,466</td>
<td align="right">14.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">37,439,901</td>
<td align="right">7.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">16,255,000</td>
<td align="right">3.4%</td>
</tr>
<tr>
<td align="left">CALL_LEN</td>
<td align="right">2,607,700</td>
<td align="right">0.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">101,903,302</td>
<td align="right">21.4%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">80,238,760</td>
<td align="right">16.8%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">67,527,780</td>
<td align="right">14.2%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">44,597,017</td>
<td align="right">9.4%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">39,937,800</td>
<td align="right">8.4%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">135,119,169</td>
<td align="right">68.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">17,988,143</td>
<td align="right">9.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">13,997,820</td>
<td align="right">7.0%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">10,630,920</td>
<td align="right">5.3%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">10,061,120</td>
<td align="right">5.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">100,622,226</td>
<td align="right">50.6%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">36,970,660</td>
<td align="right">18.6%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">14,259,900</td>
<td align="right">7.2%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">10,418,760</td>
<td align="right">5.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">5,513,820</td>
<td align="right">2.8%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">206,245,198</td>
<td align="right">24.0%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">173,552,601</td>
<td align="right">20.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">164,505,810</td>
<td align="right">19.2%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">159,175,780</td>
<td align="right">18.6%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">96,694,080</td>
<td align="right">11.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">209,487,808</td>
<td align="right">24.5%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">198,595,380</td>
<td align="right">23.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">155,289,960</td>
<td align="right">18.1%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">90,769,097</td>
<td align="right">10.6%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">65,379,206</td>
<td align="right">7.6%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">188,665,083</td>
<td align="right">82.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">39,862,251</td>
<td align="right">17.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">420</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">240</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">60</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL</td>
<td align="right">72,000,000</td>
<td align="right">31.5%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">30,785,980</td>
<td align="right">13.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">25,813,203</td>
<td align="right">11.3%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">24,077,486</td>
<td align="right">10.5%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">19,355,040</td>
<td align="right">8.5%</td>
</tr>
</tbody>
</table>


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">20,510,360</td>
<td align="right">33.7%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">12,446,220</td>
<td align="right">20.4%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_FLOAT</td>
<td align="right">9,000,000</td>
<td align="right">14.8%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_FLOAT</td>
<td align="right">8,978,540</td>
<td align="right">14.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">2,957,478</td>
<td align="right">4.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">57,690,658</td>
<td align="right">94.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,661,260</td>
<td align="right">2.7%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">1,518,420</td>
<td align="right">2.5%</td>
</tr>
<tr>
<td align="left">CALL_ALLOC_AND_ENTER_INIT</td>
<td align="right">32,200</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">12,520</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">29,655,557</td>
<td align="right">27.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_INT</td>
<td align="right">22,513,860</td>
<td align="right">20.5%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">15,801,600</td>
<td align="right">14.4%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">6,876,055</td>
<td align="right">6.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">6,496,000</td>
<td align="right">5.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">81,842,644</td>
<td align="right">74.6%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">27,084,413</td>
<td align="right">24.7%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">662,955</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">158,868</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">240</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">39,374,255</td>
<td align="right">37.9%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">9,883,652</td>
<td align="right">9.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_INT</td>
<td align="right">7,662,580</td>
<td align="right">7.4%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">6,888,220</td>
<td align="right">6.6%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">5,566,910</td>
<td align="right">5.4%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">GET_ITER</td>
<td align="right">31,651,234</td>
<td align="right">30.4%</td>
</tr>
<tr>
<td align="left">BINARY_OP_MULTIPLY_FLOAT</td>
<td align="right">24,782,880</td>
<td align="right">23.8%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">19,191,726</td>
<td align="right">18.5%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">5,566,910</td>
<td align="right">5.4%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">3,552,640</td>
<td align="right">3.4%</td>
</tr>
</tbody>
</table>


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">434,497,240</td>
<td align="right">46.9%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">280,321,989</td>
<td align="right">30.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">80,336,103</td>
<td align="right">8.7%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">40,302,733</td>
<td align="right">4.4%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">37,470,460</td>
<td align="right">4.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">486,859,720</td>
<td align="right">52.6%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">322,305,212</td>
<td align="right">34.8%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">41,908,296</td>
<td align="right">4.5%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">37,470,460</td>
<td align="right">4.0%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">9,149,854</td>
<td align="right">1.0%</td>
</tr>
</tbody>
</table>


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">48,222,060</td>
<td align="right">48.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">21,424,155</td>
<td align="right">21.5%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">5,629,780</td>
<td align="right">5.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">5,145,200</td>
<td align="right">5.2%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">5,069,740</td>
<td align="right">5.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">46,765,320</td>
<td align="right">46.9%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">19,478,675</td>
<td align="right">19.5%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">11,654,563</td>
<td align="right">11.7%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">7,264,980</td>
<td align="right">7.3%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">5,069,740</td>
<td align="right">5.1%</td>
</tr>
</tbody>
</table>


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">538,102,865</td>
<td align="right">68.0%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">80,509,140</td>
<td align="right">10.2%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">43,638,720</td>
<td align="right">5.5%</td>
</tr>
<tr>
<td align="left">BUILD_STRING</td>
<td align="right">37,276,800</td>
<td align="right">4.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_UNICODE</td>
<td align="right">19,572,000</td>
<td align="right">2.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_TOP</td>
<td align="right">379,849,320</td>
<td align="right">48.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">164,403,480</td>
<td align="right">20.8%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">137,412,900</td>
<td align="right">17.4%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">26,857,070</td>
<td align="right">3.4%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR_DICT</td>
<td align="right">14,472,780</td>
<td align="right">1.8%</td>
</tr>
</tbody>
</table>


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">156,541,255</td>
<td align="right">38.8%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">138,285,276</td>
<td align="right">34.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">61,137,079</td>
<td align="right">15.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">21,233,060</td>
<td align="right">5.3%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">9,774,334</td>
<td align="right">2.4%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">392,171,827</td>
<td align="right">97.2%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">5,172,985</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">3,093,420</td>
<td align="right">0.8%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">1,556,525</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">1,176,271</td>
<td align="right">0.3%</td>
</tr>
</tbody>
</table>


</details>

### CALL_KW_NON_PY

<details>
<summary> Successors and predecessors for CALL_KW_NON_PY </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">29,055,351</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">CALL_KW</td>
<td align="right">904</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">18,750,100</td>
<td align="right">64.5%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">5,697,583</td>
<td align="right">19.6%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">3,074,632</td>
<td align="right">10.6%</td>
</tr>
<tr>
<td align="left">STORE_ATTR</td>
<td align="right">1,200,840</td>
<td align="right">4.1%</td>
</tr>
<tr>
<td align="left">LIST_APPEND</td>
<td align="right">128,040</td>
<td align="right">0.4%</td>
</tr>
</tbody>
</table>


</details>

### CALL_KW_PY

<details>
<summary> Successors and predecessors for CALL_KW_PY </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">31,710,638</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">CALL_KW</td>
<td align="right">960</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_KW_PY</td>
<td align="right">20</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">27,450,158</td>
<td align="right">86.6%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">3,401,040</td>
<td align="right">10.7%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">728,640</td>
<td align="right">2.3%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">131,760</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">CALL_KW_PY</td>
<td align="right">20</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">202,021,667</td>
<td align="right">73.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">34,667,860</td>
<td align="right">12.6%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">29,548,500</td>
<td align="right">10.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">3,086,160</td>
<td align="right">1.1%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">2,569,980</td>
<td align="right">0.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">115,037,692</td>
<td align="right">41.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">40,473,780</td>
<td align="right">14.7%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">35,533,074</td>
<td align="right">12.9%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">34,645,220</td>
<td align="right">12.6%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">9,746,417</td>
<td align="right">3.5%</td>
</tr>
</tbody>
</table>


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">67,965,110</td>
<td align="right">45.2%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">20,171,040</td>
<td align="right">13.4%</td>
</tr>
<tr>
<td align="left">BINARY_SLICE</td>
<td align="right">19,300,980</td>
<td align="right">12.8%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">17,923,163</td>
<td align="right">11.9%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">8,543,680</td>
<td align="right">5.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">72,247,150</td>
<td align="right">48.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">42,319,706</td>
<td align="right">28.1%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">21,236,040</td>
<td align="right">14.1%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">3,509,311</td>
<td align="right">2.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">3,445,140</td>
<td align="right">2.3%</td>
</tr>
</tbody>
</table>


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">69,733,551</td>
<td align="right">35.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">35,678,120</td>
<td align="right">18.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">35,038,860</td>
<td align="right">17.7%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">16,106,702</td>
<td align="right">8.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">8,303,280</td>
<td align="right">4.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">125,709,666</td>
<td align="right">63.5%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">14,633,560</td>
<td align="right">7.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">9,860,874</td>
<td align="right">5.0%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">8,893,800</td>
<td align="right">4.5%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">6,043,369</td>
<td align="right">3.1%</td>
</tr>
</tbody>
</table>


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">120,321,288</td>
<td align="right">88.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_LAZY_DICT</td>
<td align="right">8,733,824</td>
<td align="right">6.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">3,590,818</td>
<td align="right">2.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">3,111,120</td>
<td align="right">2.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">263,040</td>
<td align="right">0.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">GET_ITER</td>
<td align="right">43,280,843</td>
<td align="right">31.8%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">24,695,062</td>
<td align="right">18.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">18,631,740</td>
<td align="right">13.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">12,049,312</td>
<td align="right">8.8%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_CLASS</td>
<td align="right">9,883,652</td>
<td align="right">7.3%</td>
</tr>
</tbody>
</table>


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">142,106,638</td>
<td align="right">82.8%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS</td>
<td align="right">6,935,320</td>
<td align="right">4.0%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">6,020,880</td>
<td align="right">3.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">3,033,040</td>
<td align="right">1.8%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">2,536,080</td>
<td align="right">1.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">72,001,440</td>
<td align="right">41.9%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">65,523,778</td>
<td align="right">38.2%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">17,248,200</td>
<td align="right">10.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">7,492,980</td>
<td align="right">4.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">2,928,420</td>
<td align="right">1.7%</td>
</tr>
</tbody>
</table>


</details>

### CALL_NON_PY_GENERAL

<details>
<summary> Successors and predecessors for CALL_NON_PY_GENERAL </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">71,402,183</td>
<td align="right">38.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">27,370,920</td>
<td align="right">14.7%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">20,774,632</td>
<td align="right">11.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">16,481,300</td>
<td align="right">8.9%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">7,733,906</td>
<td align="right">4.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">92,577,475</td>
<td align="right">49.7%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">28,937,937</td>
<td align="right">15.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">15,998,557</td>
<td align="right">8.6%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">12,231,063</td>
<td align="right">6.6%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">9,342,752</td>
<td align="right">5.0%</td>
</tr>
</tbody>
</table>


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">670,694,939</td>
<td align="right">35.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">476,626,954</td>
<td align="right">25.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">283,497,686</td>
<td align="right">15.2%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_INT</td>
<td align="right">80,238,760</td>
<td align="right">4.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">71,023,799</td>
<td align="right">3.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">1,678,711,289</td>
<td align="right">89.9%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">105,229,219</td>
<td align="right">5.6%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">65,716,974</td>
<td align="right">3.5%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_RESUME</td>
<td align="right">14,567,400</td>
<td align="right">0.8%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">2,320,762</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">352,080,855</td>
<td align="right">99.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">3,657,390</td>
<td align="right">1.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">19,240</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">160</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">322,246,047</td>
<td align="right">90.6%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">17,744,392</td>
<td align="right">5.0%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">4,366,997</td>
<td align="right">1.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">3,040,787</td>
<td align="right">0.9%</td>
</tr>
<tr>
<td align="left">IS_OP</td>
<td align="right">2,851,090</td>
<td align="right">0.8%</td>
</tr>
</tbody>
</table>


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">23,382,660</td>
<td align="right">35.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">18,000,780</td>
<td align="right">27.4%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">14,457,600</td>
<td align="right">22.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">2,768,500</td>
<td align="right">4.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">2,400,000</td>
<td align="right">3.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">38,440,740</td>
<td align="right">58.6%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">27,194,974</td>
<td align="right">41.4%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">1,040</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">380</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">516,803,782</td>
<td align="right">40.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">202,939,399</td>
<td align="right">15.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">121,683,325</td>
<td align="right">9.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">115,462,448</td>
<td align="right">9.0%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">100,011,960</td>
<td align="right">7.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">1,072,602,673</td>
<td align="right">83.9%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">107,537,915</td>
<td align="right">8.4%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">59,838,898</td>
<td align="right">4.7%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">14,567,340</td>
<td align="right">1.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">10,481,040</td>
<td align="right">0.8%</td>
</tr>
</tbody>
</table>


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">147,841,040</td>
<td align="right">76.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">17,069,400</td>
<td align="right">8.9%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">8,508,431</td>
<td align="right">4.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">7,753,340</td>
<td align="right">4.0%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">3,333,780</td>
<td align="right">1.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">86,887,336</td>
<td align="right">45.2%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">73,423,560</td>
<td align="right">38.2%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">19,256,303</td>
<td align="right">10.0%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">7,458,420</td>
<td align="right">3.9%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">3,404,820</td>
<td align="right">1.8%</td>
</tr>
</tbody>
</table>


</details>

### CONTAINS_OP_SET

<details>
<summary> Successors and predecessors for CONTAINS_OP_SET </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">321,138,480</td>
<td align="right">87.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">36,794,800</td>
<td align="right">10.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">4,366,691</td>
<td align="right">1.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">3,064,920</td>
<td align="right">0.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_NO_DICT</td>
<td align="right">1,305,420</td>
<td align="right">0.4%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">359,112,331</td>
<td align="right">97.9%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">2,850,960</td>
<td align="right">0.8%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">1,993,800</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">1,860,600</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">865,320</td>
<td align="right">0.2%</td>
</tr>
</tbody>
</table>


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">837,343,598</td>
<td align="right">78.0%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">217,972,076</td>
<td align="right">20.3%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">16,303,669</td>
<td align="right">1.5%</td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">1,217,098</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">3,479</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">554,992,487</td>
<td align="right">51.7%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">285,029,002</td>
<td align="right">26.6%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">95,736,959</td>
<td align="right">8.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">44,246,511</td>
<td align="right">4.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">40,052,560</td>
<td align="right">3.7%</td>
</tr>
</tbody>
</table>


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">411,642,200</td>
<td align="right">92.6%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">31,248,581</td>
<td align="right">7.0%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">1,567,260</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">960</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">80</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">395,933,000</td>
<td align="right">89.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">21,849,780</td>
<td align="right">4.9%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">11,477,580</td>
<td align="right">2.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">4,093,213</td>
<td align="right">0.9%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">3,183,549</td>
<td align="right">0.7%</td>
</tr>
</tbody>
</table>


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">183,264,876</td>
<td align="right">71.6%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">70,116,582</td>
<td align="right">27.4%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">1,384,380</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">1,210,877</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">9,961</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">178,280,627</td>
<td align="right">69.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">41,375,220</td>
<td align="right">16.2%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">12,446,591</td>
<td align="right">4.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">11,986,120</td>
<td align="right">4.7%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">4,147,679</td>
<td align="right">1.6%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">2,983,095,508</td>
<td align="right">86.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">284,928,264</td>
<td align="right">8.3%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">77,818,240</td>
<td align="right">2.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">60,494,385</td>
<td align="right">1.8%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">23,171,740</td>
<td align="right">0.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,070,245,351</td>
<td align="right">31.1%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">400,358,471</td>
<td align="right">11.6%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">202,939,399</td>
<td align="right">5.9%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">139,175,783</td>
<td align="right">4.0%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">128,874,377</td>
<td align="right">3.7%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">451,888,752</td>
<td align="right">57.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">112,588,052</td>
<td align="right">14.3%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">72,025,620</td>
<td align="right">9.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">24,846,180</td>
<td align="right">3.1%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">18,775,620</td>
<td align="right">2.4%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">387,006,773</td>
<td align="right">49.1%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">120,321,288</td>
<td align="right">15.3%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">85,448,498</td>
<td align="right">10.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">60,015,130</td>
<td align="right">7.6%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">35,678,120</td>
<td align="right">4.5%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,365,841,714</td>
<td align="right">90.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">57,285,600</td>
<td align="right">3.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_WITH_HINT</td>
<td align="right">23,239,300</td>
<td align="right">1.5%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">18,260,050</td>
<td align="right">1.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">15,702,225</td>
<td align="right">1.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">675,325,395</td>
<td align="right">44.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">423,732,770</td>
<td align="right">28.1%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">283,497,686</td>
<td align="right">18.8%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">50,530,720</td>
<td align="right">3.4%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">30,516,220</td>
<td align="right">2.0%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">192,656,621</td>
<td align="right">92.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">13,982,420</td>
<td align="right">6.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">633,720</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">335,160</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_WITH_HINT</td>
<td align="right">14,460</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">145,016,023</td>
<td align="right">69.8%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE</td>
<td align="right">21,233,060</td>
<td align="right">10.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">13,982,420</td>
<td align="right">6.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">13,108,140</td>
<td align="right">6.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">4,925,780</td>
<td align="right">2.4%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">41,737,432</td>
<td align="right">83.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">4,374,880</td>
<td align="right">8.7%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">2,950,713</td>
<td align="right">5.9%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">398,520</td>
<td align="right">0.8%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">233,865</td>
<td align="right">0.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">35,530,629</td>
<td align="right">70.8%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">3,993,374</td>
<td align="right">8.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">3,322,015</td>
<td align="right">6.6%</td>
</tr>
<tr>
<td align="left">PUSH_EXC_INFO</td>
<td align="right">3,258,540</td>
<td align="right">6.5%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">1,435,408</td>
<td align="right">2.9%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">558,487,493</td>
<td align="right">79.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">80,213,480</td>
<td align="right">11.3%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">40,131,480</td>
<td align="right">5.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">14,952,331</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">6,981,480</td>
<td align="right">1.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">226,604,588</td>
<td align="right">32.0%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">58,268,820</td>
<td align="right">8.2%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">52,894,401</td>
<td align="right">7.5%</td>
</tr>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">45,905,880</td>
<td align="right">6.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">44,104,809</td>
<td align="right">6.2%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_CONST_IMMORTAL

<details>
<summary> Successors and predecessors for LOAD_CONST_IMMORTAL </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">619,444,694</td>
<td align="right">19.9%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">529,232,706</td>
<td align="right">17.0%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">243,700,181</td>
<td align="right">7.8%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">165,841,903</td>
<td align="right">5.3%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">164,403,480</td>
<td align="right">5.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">819,497,895</td>
<td align="right">26.4%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">529,232,706</td>
<td align="right">17.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">314,023,626</td>
<td align="right">10.1%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">280,321,989</td>
<td align="right">9.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">250,307,155</td>
<td align="right">8.1%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">892,660,741</td>
<td align="right">27.1%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">806,182,676</td>
<td align="right">24.4%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">659,929,206</td>
<td align="right">20.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">474,454,465</td>
<td align="right">14.4%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">84,025,807</td>
<td align="right">2.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">2,214,472,866</td>
<td align="right">67.1%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">434,497,240</td>
<td align="right">13.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_CLASS</td>
<td align="right">220,646,818</td>
<td align="right">6.7%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE</td>
<td align="right">156,541,255</td>
<td align="right">4.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">124,861,047</td>
<td align="right">3.8%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">723,105,793</td>
<td align="right">38.6%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">170,325,439</td>
<td align="right">9.1%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">163,498,978</td>
<td align="right">8.7%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">146,002,159</td>
<td align="right">7.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">85,428,939</td>
<td align="right">4.6%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">408,979,464</td>
<td align="right">21.8%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_SET</td>
<td align="right">321,138,480</td>
<td align="right">17.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">192,656,621</td>
<td align="right">10.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">139,927,850</td>
<td align="right">7.5%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE</td>
<td align="right">138,285,276</td>
<td align="right">7.4%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">35,824,428</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">LOAD_SUPER_ATTR</td>
<td align="right">160</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">30,898,620</td>
<td align="right">86.2%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">2,139,514</td>
<td align="right">6.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">1,496,225</td>
<td align="right">4.2%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">1,185,780</td>
<td align="right">3.3%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">104,349</td>
<td align="right">0.3%</td>
</tr>
</tbody>
</table>


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">1,678,711,289</td>
<td align="right">43.8%</td>
</tr>
<tr>
<td align="left">CACHE</td>
<td align="right">823,262,076</td>
<td align="right">21.5%</td>
</tr>
<tr>
<td align="left">SEND_GEN</td>
<td align="right">373,371,480</td>
<td align="right">9.7%</td>
</tr>
<tr>
<td align="left">CALL_PY_GENERAL</td>
<td align="right">224,234,621</td>
<td align="right">5.8%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">198,022,620</td>
<td align="right">5.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,429,055,295</td>
<td align="right">37.3%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">659,929,206</td>
<td align="right">17.2%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">562,680,691</td>
<td align="right">14.7%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD_NO_INTERRUPT</td>
<td align="right">373,516,200</td>
<td align="right">9.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">212,163,522</td>
<td align="right">5.5%</td>
</tr>
</tbody>
</table>


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">320,847,383</td>
<td align="right">44.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">289,709,621</td>
<td align="right">40.4%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">76,960,660</td>
<td align="right">10.7%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">21,166,620</td>
<td align="right">2.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">7,344,860</td>
<td align="right">1.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">342,607,891</td>
<td align="right">47.7%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">165,841,903</td>
<td align="right">23.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">127,530,800</td>
<td align="right">17.8%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">24,907,920</td>
<td align="right">3.5%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">21,891,214</td>
<td align="right">3.0%</td>
</tr>
</tbody>
</table>


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">140,511,301</td>
<td align="right">50.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">99,115,931</td>
<td align="right">35.4%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">40,131,480</td>
<td align="right">14.3%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_SLOT</td>
<td align="right">157,170</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">25,140</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">120,838,981</td>
<td align="right">43.2%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">104,617,438</td>
<td align="right">37.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">36,129,776</td>
<td align="right">12.9%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">6,653,040</td>
<td align="right">2.4%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">6,187,680</td>
<td align="right">2.2%</td>
</tr>
</tbody>
</table>


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">89,951,492</td>
<td align="right">55.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">31,594,116</td>
<td align="right">19.5%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">14,472,780</td>
<td align="right">8.9%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">8,276,060</td>
<td align="right">5.1%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_TUPLE_INT</td>
<td align="right">3,815,040</td>
<td align="right">2.4%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">88,038,540</td>
<td align="right">54.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">33,072,804</td>
<td align="right">20.4%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">28,966,972</td>
<td align="right">17.9%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">7,819,732</td>
<td align="right">4.8%</td>
</tr>
<tr>
<td align="left">POP_EXCEPT</td>
<td align="right">3,189,120</td>
<td align="right">2.0%</td>
</tr>
</tbody>
</table>


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">654,140,963</td>
<td align="right">27.8%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST</td>
<td align="right">486,859,720</td>
<td align="right">20.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">400,358,471</td>
<td align="right">17.0%</td>
</tr>
<tr>
<td align="left">CALL_ISINSTANCE</td>
<td align="right">392,171,827</td>
<td align="right">16.7%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">181,577,686</td>
<td align="right">7.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">1,656,448,842</td>
<td align="right">70.4%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">590,053,629</td>
<td align="right">25.1%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">85,225,182</td>
<td align="right">3.6%</td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">21,473,579</td>
<td align="right">0.9%</td>
</tr>
<tr>
<td align="left">TO_BOOL_INT</td>
<td align="right">12,900</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">157,146,615</td>
<td align="right">75.9%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">12,835,620</td>
<td align="right">6.2%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">10,121,256</td>
<td align="right">4.9%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">7,990,454</td>
<td align="right">3.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">6,823,200</td>
<td align="right">3.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">167,792,552</td>
<td align="right">81.0%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">31,340,517</td>
<td align="right">15.1%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">6,985,680</td>
<td align="right">3.4%</td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">931,320</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">12,920</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### TO_BOOL_LIST

<details>
<summary> Successors and predecessors for TO_BOOL_LIST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">54,292,505</td>
<td align="right">84.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">6,773,160</td>
<td align="right">10.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">1,712,180</td>
<td align="right">2.7%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">604,198</td>
<td align="right">0.9%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_DICT</td>
<td align="right">423,540</td>
<td align="right">0.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">32,420,858</td>
<td align="right">50.6%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">29,837,041</td>
<td align="right">46.6%</td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">1,234,749</td>
<td align="right">1.9%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">496,740</td>
<td align="right">0.8%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">24,367</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">240,709,689</td>
<td align="right">44.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">201,844,624</td>
<td align="right">37.5%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">24,808,480</td>
<td align="right">4.6%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">14,633,560</td>
<td align="right">2.7%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_DICT</td>
<td align="right">14,259,900</td>
<td align="right">2.6%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">255,856,800</td>
<td align="right">47.5%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">243,730,103</td>
<td align="right">45.2%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_LIST</td>
<td align="right">24,026,440</td>
<td align="right">4.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">15,130,320</td>
<td align="right">2.8%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TWO_TUPLE</td>
<td align="right">29,880</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">285,029,002</td>
<td align="right">50.6%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">194,372,956</td>
<td align="right">34.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">36,675,533</td>
<td align="right">6.5%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">32,586,263</td>
<td align="right">5.8%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">5,825,006</td>
<td align="right">1.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">332,090,356</td>
<td align="right">58.9%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">215,310,375</td>
<td align="right">38.2%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">12,001,200</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">3,356,640</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,084,980</td>
<td align="right">0.2%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_OP_INPLACE_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_INPLACE_ADD_UNICODE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">1,007,880</td>
<td align="right">41.6%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">532,380</td>
<td align="right">22.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">358,800</td>
<td align="right">14.8%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_STR_INT</td>
<td align="right">217,140</td>
<td align="right">9.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_UNICODE</td>
<td align="right">204,820</td>
<td align="right">8.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,585,980</td>
<td align="right">65.5%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">738,220</td>
<td align="right">30.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">60,360</td>
<td align="right">2.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">22,860</td>
<td align="right">0.9%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">8,820</td>
<td align="right">0.4%</td>
</tr>
</tbody>
</table>


</details>

### FORMAT_SIMPLE

<details>
<summary> Successors and predecessors for FORMAT_SIMPLE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CONVERT_VALUE</td>
<td align="right">105,612,540</td>
<td align="right">96.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">1,423,980</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,052,100</td>
<td align="right">1.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">831,600</td>
<td align="right">0.8%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">732,120</td>
<td align="right">0.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">50,409,300</td>
<td align="right">46.0%</td>
</tr>
<tr>
<td align="left">BUILD_STRING</td>
<td align="right">48,947,640</td>
<td align="right">44.6%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">7,098,300</td>
<td align="right">6.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">3,196,260</td>
<td align="right">2.9%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">8,820</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">104,051,700</td>
<td align="right">99.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">263,400</td>
<td align="right">0.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">103,874,760</td>
<td align="right">99.6%</td>
</tr>
<tr>
<td align="left">DELETE_SUBSCR</td>
<td align="right">440,340</td>
<td align="right">0.4%</td>
</tr>
</tbody>
</table>


</details>

### BUILD_STRING

<details>
<summary> Successors and predecessors for BUILD_STRING </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">FORMAT_SIMPLE</td>
<td align="right">48,947,640</td>
<td align="right">88.7%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">6,234,000</td>
<td align="right">11.3%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">28,800</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">37,276,800</td>
<td align="right">67.5%</td>
</tr>
<tr>
<td align="left">CALL_PY_GENERAL</td>
<td align="right">11,581,020</td>
<td align="right">21.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_UNICODE</td>
<td align="right">2,010,960</td>
<td align="right">3.6%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">1,863,540</td>
<td align="right">3.4%</td>
</tr>
<tr>
<td align="left">CALL_LIST_APPEND</td>
<td align="right">1,398,120</td>
<td align="right">2.5%</td>
</tr>
</tbody>
</table>


</details>

### CONVERT_VALUE

<details>
<summary> Successors and predecessors for CONVERT_VALUE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">87,664,260</td>
<td align="right">83.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">11,580,660</td>
<td align="right">11.0%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">2,010,960</td>
<td align="right">1.9%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">1,496,100</td>
<td align="right">1.4%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">1,385,580</td>
<td align="right">1.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">FORMAT_SIMPLE</td>
<td align="right">105,612,540</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### DELETE_ATTR

<details>
<summary> Successors and predecessors for DELETE_ATTR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">72,360</td>
<td align="right">99.9%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">60</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">46,000</td>
<td align="right">63.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">23,340</td>
<td align="right">32.2%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">2,600</td>
<td align="right">3.6%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">480</td>
<td align="right">0.7%</td>
</tr>
</tbody>
</table>


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">24,443,527</td>
<td align="right">98.4%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">172,652</td>
<td align="right">0.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">132,720</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">50,880</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">19,680</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">24,832,599</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### IMPORT_NAME

<details>
<summary> Successors and predecessors for IMPORT_NAME </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">5,714,685</td>
<td align="right">95.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">299,580</td>
<td align="right">5.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">IMPORT_FROM</td>
<td align="right">5,715,165</td>
<td align="right">95.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">299,100</td>
<td align="right">5.0%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_SPECIAL

<details>
<summary> Successors and predecessors for LOAD_SPECIAL </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">COPY</td>
<td align="right">6,534,228</td>
<td align="right">50.0%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">6,534,228</td>
<td align="right">50.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">SWAP</td>
<td align="right">6,534,228</td>
<td align="right">50.0%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">4,995,040</td>
<td align="right">38.2%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">1,532,748</td>
<td align="right">11.7%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">6,080</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL</td>
<td align="right">360</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">95,437,662</td>
<td align="right">60.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">35,096,360</td>
<td align="right">22.2%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">16,507,980</td>
<td align="right">10.5%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">5,142,324</td>
<td align="right">3.3%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">2,080,759</td>
<td align="right">1.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">105,031,288</td>
<td align="right">66.5%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">20,434,223</td>
<td align="right">12.9%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">13,007,687</td>
<td align="right">8.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">10,625,836</td>
<td align="right">6.7%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">3,405,480</td>
<td align="right">2.2%</td>
</tr>
</tbody>
</table>


</details>

### RAISE_VARARGS

<details>
<summary> Successors and predecessors for RAISE_VARARGS </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">583,740</td>
<td align="right">44.4%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">543,240</td>
<td align="right">41.3%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">137,230</td>
<td align="right">10.4%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">32,160</td>
<td align="right">2.4%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">16,080</td>
<td align="right">1.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">PUSH_EXC_INFO</td>
<td align="right">885,430</td>
<td align="right">67.4%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">427,500</td>
<td align="right">32.6%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">180</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### RERAISE

<details>
<summary> Successors and predecessors for RERAISE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_EXCEPT</td>
<td align="right">932,040</td>
<td align="right">65.2%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">377,940</td>
<td align="right">26.5%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">113,700</td>
<td align="right">8.0%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">4,080</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">480</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">PUSH_EXC_INFO</td>
<td align="right">926,760</td>
<td align="right">65.1%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">495,900</td>
<td align="right">34.9%</td>
</tr>
</tbody>
</table>


</details>

### STORE_GLOBAL

<details>
<summary> Successors and predecessors for STORE_GLOBAL </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">6,147,600</td>
<td align="right">99.9%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">3,900</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">120</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">60</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">4,863,540</td>
<td align="right">79.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">1,285,980</td>
<td align="right">20.9%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">1,920</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">180</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">60</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### UNPACK_EX

<details>
<summary> Successors and predecessors for UNPACK_EX </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">280,800</td>
<td align="right">56.1%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">218,520</td>
<td align="right">43.7%</td>
</tr>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">960</td>
<td align="right">0.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">500,280</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">35,995,100</td>
<td align="right">66.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">10,307,040</td>
<td align="right">18.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">2,460,900</td>
<td align="right">4.5%</td>
</tr>
<tr>
<td align="left">BUILD_STRING</td>
<td align="right">2,010,960</td>
<td align="right">3.7%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">981,120</td>
<td align="right">1.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">19,572,000</td>
<td align="right">35.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">14,207,880</td>
<td align="right">26.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">10,101,000</td>
<td align="right">18.5%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">2,963,340</td>
<td align="right">5.4%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">2,457,600</td>
<td align="right">4.5%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">66,766,920</td>
<td align="right">61.6%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">28,812,000</td>
<td align="right">26.6%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">3,532,566</td>
<td align="right">3.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">3,355,020</td>
<td align="right">3.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">3,132,720</td>
<td align="right">2.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">108,321,700</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">12,472</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">3,020</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">2,400</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">BUILD_LIST</td>
<td align="right">1,200</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_SUBSCR_STR_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_STR_INT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP_SUBTRACT_INT</td>
<td align="right">10,611,960</td>
<td align="right">26.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">10,356,180</td>
<td align="right">25.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">10,176,060</td>
<td align="right">25.0%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">5,293,080</td>
<td align="right">13.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">3,715,200</td>
<td align="right">9.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">20,811,000</td>
<td align="right">51.2%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">10,375,320</td>
<td align="right">25.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">5,145,480</td>
<td align="right">12.7%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">3,711,600</td>
<td align="right">9.1%</td>
</tr>
<tr>
<td align="left">BINARY_OP_INPLACE_ADD_UNICODE</td>
<td align="right">217,140</td>
<td align="right">0.5%</td>
</tr>
</tbody>
</table>


</details>

### CALL_KW_BOUND_METHOD

<details>
<summary> Successors and predecessors for CALL_KW_BOUND_METHOD </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">1,440,320</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">CALL_KW</td>
<td align="right">40</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">1,440,360</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">54,958,560</td>
<td align="right">71.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">8,481,660</td>
<td align="right">11.1%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">7,909,460</td>
<td align="right">10.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">3,629,560</td>
<td align="right">4.7%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">1,133,100</td>
<td align="right">1.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">59,070,220</td>
<td align="right">77.3%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_O</td>
<td align="right">6,935,320</td>
<td align="right">9.1%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">3,414,780</td>
<td align="right">4.5%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">2,919,060</td>
<td align="right">3.8%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">2,010,960</td>
<td align="right">2.6%</td>
</tr>
</tbody>
</table>


</details>

### CALL_PY_GENERAL

<details>
<summary> Successors and predecessors for CALL_PY_GENERAL </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">83,255,800</td>
<td align="right">35.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">81,029,805</td>
<td align="right">34.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">16,457,345</td>
<td align="right">7.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">14,785,982</td>
<td align="right">6.3%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">11,667,444</td>
<td align="right">5.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">224,234,621</td>
<td align="right">95.7%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">8,777,824</td>
<td align="right">3.7%</td>
</tr>
<tr>
<td align="left">MAKE_CELL</td>
<td align="right">949,388</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">229,320</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">CALL_PY_GENERAL</td>
<td align="right">43,780</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">5,391,220</td>
<td align="right">49.6%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_FAST_WITH_KEYWORDS</td>
<td align="right">3,487,700</td>
<td align="right">32.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,258,399</td>
<td align="right">11.6%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">412,080</td>
<td align="right">3.8%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">163,620</td>
<td align="right">1.5%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">3,490,720</td>
<td align="right">32.1%</td>
</tr>
<tr>
<td align="left">BUILD_TUPLE</td>
<td align="right">2,504,040</td>
<td align="right">23.0%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">2,419,200</td>
<td align="right">22.2%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">995,204</td>
<td align="right">9.2%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">465,660</td>
<td align="right">4.3%</td>
</tr>
</tbody>
</table>


</details>

### CONTAINS_OP_DICT

<details>
<summary> Successors and predecessors for CONTAINS_OP_DICT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">112,976,939</td>
<td align="right">59.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">31,374,265</td>
<td align="right">16.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_CLASS_WITH_METACLASS_CHECK</td>
<td align="right">14,498,056</td>
<td align="right">7.7%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">11,065,080</td>
<td align="right">5.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">5,732,180</td>
<td align="right">3.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">131,929,948</td>
<td align="right">69.7%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">54,683,598</td>
<td align="right">28.9%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">1,691,880</td>
<td align="right">0.9%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">843,900</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_SET</td>
<td align="right">11,780</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">220,646,818</td>
<td align="right">69.1%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">96,465,520</td>
<td align="right">30.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,402,400</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">591,660</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">49,020</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">IS_OP</td>
<td align="right">216,000,120</td>
<td align="right">67.7%</td>
</tr>
<tr>
<td align="left">COMPARE_OP_INT</td>
<td align="right">56,745,600</td>
<td align="right">17.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">23,894,058</td>
<td align="right">7.5%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">12,371,400</td>
<td align="right">3.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">4,211,200</td>
<td align="right">1.3%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR_CLASS_WITH_METACLASS_CHECK

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS_WITH_METACLASS_CHECK </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">14,946,694</td>
<td align="right">95.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">713,580</td>
<td align="right">4.5%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">26,280</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">4,014</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_TYPE_1</td>
<td align="right">2,040</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CONTAINS_OP_DICT</td>
<td align="right">14,498,056</td>
<td align="right">92.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">408,978</td>
<td align="right">2.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">396,330</td>
<td align="right">2.5%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">243,180</td>
<td align="right">1.5%</td>
</tr>
<tr>
<td align="left">CALL_FUNCTION_EX</td>
<td align="right">57,900</td>
<td align="right">0.4%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR_METHOD_LAZY_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_LAZY_DICT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">35,897,940</td>
<td align="right">64.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">19,878,120</td>
<td align="right">35.6%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">5,760</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">600</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">480</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">39,463,220</td>
<td align="right">70.7%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_NOARGS</td>
<td align="right">8,733,824</td>
<td align="right">15.7%</td>
</tr>
<tr>
<td align="left">LOAD_SMALL_INT</td>
<td align="right">4,802,760</td>
<td align="right">8.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">2,457,600</td>
<td align="right">4.4%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">192,140</td>
<td align="right">0.3%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">171,701,741</td>
<td align="right">89.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">18,012,986</td>
<td align="right">9.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">834,617</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">221,320</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">187,240</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">55,223,280</td>
<td align="right">28.9%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">27,216,680</td>
<td align="right">14.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">26,741,925</td>
<td align="right">14.0%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">19,478,160</td>
<td align="right">10.2%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">12,757,920</td>
<td align="right">6.7%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for LOAD_ATTR_WITH_HINT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">22,919,040</td>
<td align="right">43.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_WITH_HINT</td>
<td align="right">13,644,060</td>
<td align="right">26.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">13,620,380</td>
<td align="right">26.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">1,247,920</td>
<td align="right">2.4%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">477,240</td>
<td align="right">0.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">23,239,300</td>
<td align="right">44.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_WITH_HINT</td>
<td align="right">13,644,060</td>
<td align="right">26.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">7,453,000</td>
<td align="right">14.2%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">3,643,360</td>
<td align="right">6.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">2,128,300</td>
<td align="right">4.1%</td>
</tr>
</tbody>
</table>


</details>

### STORE_ATTR_WITH_HINT

<details>
<summary> Successors and predecessors for STORE_ATTR_WITH_HINT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">3,897,120</td>
<td align="right">51.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">3,491,180</td>
<td align="right">45.8%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">220,980</td>
<td align="right">2.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">4,860</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">160</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">3,763,740</td>
<td align="right">49.4%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">3,702,360</td>
<td align="right">48.6%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">75,580</td>
<td align="right">1.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">59,940</td>
<td align="right">0.8%</td>
</tr>
<tr>
<td align="left">BUILD_LIST</td>
<td align="right">4,980</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>


</details>

### TO_BOOL_ALWAYS_TRUE

<details>
<summary> Successors and predecessors for TO_BOOL_ALWAYS_TRUE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">67,616,960</td>
<td align="right">59.2%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">23,777,772</td>
<td align="right">20.8%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">13,423,520</td>
<td align="right">11.8%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">6,549,724</td>
<td align="right">5.7%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_DICT</td>
<td align="right">1,032,000</td>
<td align="right">0.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">86,202,744</td>
<td align="right">75.5%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">27,358,420</td>
<td align="right">24.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">389,560</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">160,920</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">TO_BOOL_ALWAYS_TRUE</td>
<td align="right">91,800</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">124,732,711</td>
<td align="right">49.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">87,743,640</td>
<td align="right">34.5%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">15,246,592</td>
<td align="right">6.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">10,277,080</td>
<td align="right">4.0%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">7,726,600</td>
<td align="right">3.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">225,265,780</td>
<td align="right">88.5%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">28,319,794</td>
<td align="right">11.1%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">515,120</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">TO_BOOL_ALWAYS_TRUE</td>
<td align="right">389,560</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">53,700</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">40,845,220</td>
<td align="right">70.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">6,813,060</td>
<td align="right">11.7%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">3,814,380</td>
<td align="right">6.5%</td>
</tr>
<tr>
<td align="left">COPY</td>
<td align="right">2,830,620</td>
<td align="right">4.9%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">2,457,600</td>
<td align="right">4.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_TRUE</td>
<td align="right">30,052,140</td>
<td align="right">51.5%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">27,897,000</td>
<td align="right">47.8%</td>
</tr>
<tr>
<td align="left">UNARY_NOT</td>
<td align="right">323,040</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">32,740</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">12,000</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### INSTRUMENTED_RESUME

<details>
<summary> Successors and predecessors for INSTRUMENTED_RESUME </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">14,567,400</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">240</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">120</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_RESUME</td>
<td align="right">60</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">INSTRUMENTED_LINE</td>
<td align="right">14,567,400</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">300</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">60</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_RESUME</td>
<td align="right">60</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### INSTRUMENTED_RETURN_VALUE

<details>
<summary> Successors and predecessors for INSTRUMENTED_RETURN_VALUE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">7,283,640</td>
<td align="right">50.0%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">7,283,520</td>
<td align="right">50.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">180</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">60</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">7,283,520</td>
<td align="right">50.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">7,283,520</td>
<td align="right">50.0%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">240</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">120</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### INSTRUMENTED_JUMP_BACKWARD

<details>
<summary> Successors and predecessors for INSTRUMENTED_JUMP_BACKWARD </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_TOP</td>
<td align="right">60</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">INSTRUMENTED_LINE</td>
<td align="right">60</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### INSTRUMENTED_LINE

<details>
<summary> Successors and predecessors for INSTRUMENTED_LINE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_JUMP_IF_FALSE</td>
<td align="right">14,567,400</td>
<td align="right">50.0%</td>
</tr>
<tr>
<td align="left">INSTRUMENTED_RESUME</td>
<td align="right">14,567,400</td>
<td align="right">50.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">360</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">240</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">180</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">21,852,060</td>
<td align="right">75.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL</td>
<td align="right">7,283,700</td>
<td align="right">25.0%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">240</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">120</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### END_ASYNC_FOR

<details>
<summary> Successors and predecessors for END_ASYNC_FOR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">SEND</td>
<td align="right">6,000,000</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD_NO_INTERRUPT</td>
<td align="right">3,932,100</td>
<td align="right">65.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">2,067,900</td>
<td align="right">34.5%</td>
</tr>
</tbody>
</table>


</details>

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">SEND</td>
<td align="right">94,269,920</td>
<td align="right">52.4%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">85,578,060</td>
<td align="right">47.6%</td>
</tr>
<tr>
<td align="left">SEND_GEN</td>
<td align="right">6,400</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">94,136,760</td>
<td align="right">52.3%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">29,134,080</td>
<td align="right">16.2%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">29,134,080</td>
<td align="right">16.2%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">27,449,460</td>
<td align="right">15.3%</td>
</tr>
</tbody>
</table>


</details>

### GET_AITER

<details>
<summary> Successors and predecessors for GET_AITER </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">5,999,940</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">60</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">GET_ANEXT</td>
<td align="right">6,000,000</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### GET_ANEXT

<details>
<summary> Successors and predecessors for GET_ANEXT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">94,136,760</td>
<td align="right">94.0%</td>
</tr>
<tr>
<td align="left">GET_AITER</td>
<td align="right">6,000,000</td>
<td align="right">6.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">100,136,760</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">10,491,905</td>
<td align="right">95.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">338,806</td>
<td align="right">3.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">122,100</td>
<td align="right">1.1%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">8,820</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_MODULE</td>
<td align="right">60</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">10,961,691</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### UNARY_NOT

<details>
<summary> Successors and predecessors for UNARY_NOT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">21,473,579</td>
<td align="right">80.8%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">2,531,397</td>
<td align="right">9.5%</td>
</tr>
<tr>
<td align="left">TO_BOOL_LIST</td>
<td align="right">1,234,749</td>
<td align="right">4.6%</td>
</tr>
<tr>
<td align="left">TO_BOOL_INT</td>
<td align="right">931,320</td>
<td align="right">3.5%</td>
</tr>
<tr>
<td align="left">TO_BOOL_STR</td>
<td align="right">323,040</td>
<td align="right">1.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">COPY</td>
<td align="right">15,051,273</td>
<td align="right">56.6%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">8,970,921</td>
<td align="right">33.7%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">1,003,286</td>
<td align="right">3.8%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">747,000</td>
<td align="right">2.8%</td>
</tr>
<tr>
<td align="left">BUILD_MAP</td>
<td align="right">551,040</td>
<td align="right">2.1%</td>
</tr>
</tbody>
</table>


</details>

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">58,268,220</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">58,268,220</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### JUMP_BACKWARD_NO_INTERRUPT

<details>
<summary> Successors and predecessors for JUMP_BACKWARD_NO_INTERRUPT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">373,516,200</td>
<td align="right">98.9%</td>
</tr>
<tr>
<td align="left">END_ASYNC_FOR</td>
<td align="right">3,932,100</td>
<td align="right">1.0%</td>
</tr>
<tr>
<td align="left">POP_EXCEPT</td>
<td align="right">176,659</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">88,630</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">DELETE_FAST</td>
<td align="right">60</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">SEND_GEN</td>
<td align="right">373,377,860</td>
<td align="right">98.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">4,052,580</td>
<td align="right">1.1%</td>
</tr>
<tr>
<td align="left">SEND</td>
<td align="right">138,340</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">81,345</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">NOP</td>
<td align="right">34,925</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### CALL_BOUND_METHOD_GENERAL

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_GENERAL </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">5,984,906</td>
<td align="right">80.7%</td>
</tr>
<tr>
<td align="left">BINARY_OP_ADD_INT</td>
<td align="right">600,000</td>
<td align="right">8.1%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">588,840</td>
<td align="right">7.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">168,907</td>
<td align="right">2.3%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">29,160</td>
<td align="right">0.4%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">7,399,673</td>
<td align="right">99.8%</td>
</tr>
<tr>
<td align="left">COPY_FREE_VARS</td>
<td align="right">12,940</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">CALL_BOUND_METHOD_EXACT_ARGS</td>
<td align="right">540</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">200</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD_NO_INTERRUPT</td>
<td align="right">373,377,860</td>
<td align="right">81.4%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">85,597,524</td>
<td align="right">18.6%</td>
</tr>
<tr>
<td align="left">SEND</td>
<td align="right">260</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">373,371,480</td>
<td align="right">81.3%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">85,591,144</td>
<td align="right">18.6%</td>
</tr>
<tr>
<td align="left">END_SEND</td>
<td align="right">6,400</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">6,380</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">SEND</td>
<td align="right">240</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">40,527,360</td>
<td align="right">90.3%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">2,457,600</td>
<td align="right">5.5%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">1,734,700</td>
<td align="right">3.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">109,200</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">25,440</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">10,852,320</td>
<td align="right">24.2%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">10,848,480</td>
<td align="right">24.2%</td>
</tr>
<tr>
<td align="left">YIELD_VALUE</td>
<td align="right">7,681,920</td>
<td align="right">17.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">5,480,400</td>
<td align="right">12.2%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">3,358,200</td>
<td align="right">7.5%</td>
</tr>
</tbody>
</table>


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">SWAP</td>
<td align="right">159,175,780</td>
<td align="right">58.9%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">47,313,757</td>
<td align="right">17.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">26,430,826</td>
<td align="right">9.8%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">20,171,040</td>
<td align="right">7.5%</td>
</tr>
<tr>
<td align="left">BINARY_OP_SUBTRACT_INT</td>
<td align="right">16,239,000</td>
<td align="right">6.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">96,709,864</td>
<td align="right">35.8%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">89,159,180</td>
<td align="right">33.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">78,882,839</td>
<td align="right">29.2%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">4,925,580</td>
<td align="right">1.8%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">230,400</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_BUILD_CLASS

<details>
<summary> Successors and predecessors for LOAD_BUILD_CLASS </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">1,200</td>
<td align="right">90.9%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">120</td>
<td align="right">9.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">1,320</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_LOCALS

<details>
<summary> Successors and predecessors for LOAD_LOCALS </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_NAME</td>
<td align="right">1,320</td>
<td align="right">48.9%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">1,200</td>
<td align="right">44.4%</td>
</tr>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">180</td>
<td align="right">6.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FROM_DICT_OR_DEREF</td>
<td align="right">1,380</td>
<td align="right">51.1%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">1,320</td>
<td align="right">48.9%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_NAME

<details>
<summary> Successors and predecessors for LOAD_NAME </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">5,041,080</td>
<td align="right">56.0%</td>
</tr>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">3,961,320</td>
<td align="right">44.0%</td>
</tr>
<tr>
<td align="left">RESUME</td>
<td align="right">360</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_NAME</td>
<td align="right">180</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">60</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">4,680,900</td>
<td align="right">52.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">4,320,720</td>
<td align="right">48.0%</td>
</tr>
<tr>
<td align="left">STORE_NAME</td>
<td align="right">1,320</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">40</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE</td>
<td align="right">20</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### STORE_NAME

<details>
<summary> Successors and predecessors for STORE_NAME </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">SET_FUNCTION_ATTRIBUTE</td>
<td align="right">2,520</td>
<td align="right">22.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">2,520</td>
<td align="right">22.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">1,380</td>
<td align="right">12.3%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">1,320</td>
<td align="right">11.8%</td>
</tr>
<tr>
<td align="left">LOAD_NAME</td>
<td align="right">1,320</td>
<td align="right">11.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">4,260</td>
<td align="right">38.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">3,840</td>
<td align="right">34.2%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">1,440</td>
<td align="right">12.8%</td>
</tr>
<tr>
<td align="left">LOAD_LOCALS</td>
<td align="right">1,320</td>
<td align="right">11.8%</td>
</tr>
<tr>
<td align="left">LOAD_NAME</td>
<td align="right">180</td>
<td align="right">1.6%</td>
</tr>
</tbody>
</table>


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">38,105,807</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">POP_TOP</td>
<td align="right">38,105,807</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### GET_YIELD_FROM_ITER

<details>
<summary> Successors and predecessors for GET_YIELD_FROM_ITER </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">24,000,300</td>
<td align="right">87.4%</td>
</tr>
<tr>
<td align="left">RETURN_GENERATOR</td>
<td align="right">3,319,164</td>
<td align="right">12.1%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">132,060</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">14,160</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">27,465,684</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### DICT_UPDATE

<details>
<summary> Successors and predecessors for DICT_UPDATE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">13,140</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">DICT_MERGE</td>
<td align="right">13,140</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">79,622,054</td>
<td align="right">55.5%</td>
</tr>
<tr>
<td align="left">GET_ITER</td>
<td align="right">37,817,888</td>
<td align="right">26.3%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">26,083,460</td>
<td align="right">18.2%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">20</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">RESUME_CHECK</td>
<td align="right">105,334,614</td>
<td align="right">73.4%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">38,186,468</td>
<td align="right">26.6%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">1,260</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">480</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">340</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR_NONDESCRIPTOR_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_NO_DICT </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">54,757,084</td>
<td align="right">85.7%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">5,996,765</td>
<td align="right">9.4%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">2,324,960</td>
<td align="right">3.6%</td>
</tr>
<tr>
<td align="left">BINARY_SUBSCR_LIST_INT</td>
<td align="right">253,800</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">STORE_FAST_LOAD_FAST</td>
<td align="right">187,274</td>
<td align="right">0.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">TO_BOOL_BOOL</td>
<td align="right">33,043,805</td>
<td align="right">51.7%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_NO_DICT</td>
<td align="right">8,386,500</td>
<td align="right">13.1%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP_DICT</td>
<td align="right">5,562,060</td>
<td align="right">8.7%</td>
</tr>
<tr>
<td align="left">CALL_BUILTIN_O</td>
<td align="right">4,066,139</td>
<td align="right">6.4%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">3,272,720</td>
<td align="right">5.1%</td>
</tr>
</tbody>
</table>


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">72,992,880</td>
<td align="right">98.7%</td>
</tr>
<tr>
<td align="left">BUILD_SLICE</td>
<td align="right">440,340</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">247,440</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">233,100</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">CALL_NON_PY_GENERAL</td>
<td align="right">19,920</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">54,395,460</td>
<td align="right">73.5%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">18,000,000</td>
<td align="right">24.3%</td>
</tr>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">984,900</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">363,300</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">LOAD_FAST_LOAD_FAST</td>
<td align="right">208,140</td>
<td align="right">0.3%</td>
</tr>
</tbody>
</table>


</details>

### IMPORT_FROM

<details>
<summary> Successors and predecessors for IMPORT_FROM </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">IMPORT_NAME</td>
<td align="right">5,715,165</td>
<td align="right">88.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">639,411</td>
<td align="right">9.9%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">136,179</td>
<td align="right">2.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">4,934,224</td>
<td align="right">76.0%</td>
</tr>
<tr>
<td align="left">STORE_DEREF</td>
<td align="right">1,556,531</td>
<td align="right">24.0%</td>
</tr>
</tbody>
</table>


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">196,797,729</td>
<td align="right">86.2%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">24,026,440</td>
<td align="right">10.5%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">6,001,900</td>
<td align="right">2.6%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS</td>
<td align="right">1,128,120</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">LIST_EXTEND</td>
<td align="right">345,120</td>
<td align="right">0.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">STORE_FAST_STORE_FAST</td>
<td align="right">222,240,969</td>
<td align="right">97.3%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">6,084,480</td>
<td align="right">2.7%</td>
</tr>
<tr>
<td align="left">UNPACK_SEQUENCE_TUPLE</td>
<td align="right">24,040</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### BUILD_SET

<details>
<summary> Successors and predecessors for BUILD_SET </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">60,437</td>
<td align="right">75.9%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">18,060</td>
<td align="right">22.7%</td>
</tr>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">960</td>
<td align="right">1.2%</td>
</tr>
<tr>
<td align="left">JUMP_FORWARD</td>
<td align="right">120</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">60</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">36,600</td>
<td align="right">46.0%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">23,837</td>
<td align="right">29.9%</td>
</tr>
<tr>
<td align="left">SWAP</td>
<td align="right">18,060</td>
<td align="right">22.7%</td>
</tr>
<tr>
<td align="left">CALL_METHOD_DESCRIPTOR_FAST</td>
<td align="right">960</td>
<td align="right">1.2%</td>
</tr>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">120</td>
<td align="right">0.2%</td>
</tr>
</tbody>
</table>


</details>

### SET_ADD

<details>
<summary> Successors and predecessors for SET_ADD </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">18,180</td>
<td align="right">67.5%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">5,820</td>
<td align="right">21.6%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_PROPERTY</td>
<td align="right">2,940</td>
<td align="right">10.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">JUMP_BACKWARD</td>
<td align="right">26,940</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### SET_UPDATE

<details>
<summary> Successors and predecessors for SET_UPDATE </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_CONST</td>
<td align="right">120</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_GLOBAL_BUILTIN</td>
<td align="right">120</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">868,801</td>
<td align="right">93.7%</td>
</tr>
<tr>
<td align="left">LOAD_DEREF</td>
<td align="right">58,020</td>
<td align="right">6.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">PUSH_NULL</td>
<td align="right">926,821</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">958,080</td>
<td align="right">93.1%</td>
</tr>
<tr>
<td align="left">STORE_FAST</td>
<td align="right">58,500</td>
<td align="right">5.7%</td>
</tr>
<tr>
<td align="left">POP_JUMP_IF_NONE</td>
<td align="right">11,700</td>
<td align="right">1.1%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">660</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">POP_TOP</td>
<td align="right">480</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_GLOBAL_MODULE</td>
<td align="right">480,180</td>
<td align="right">46.6%</td>
</tr>
<tr>
<td align="left">BUILD_LIST</td>
<td align="right">479,040</td>
<td align="right">46.5%</td>
</tr>
<tr>
<td align="left">RETURN_VALUE</td>
<td align="right">57,600</td>
<td align="right">5.6%</td>
</tr>
<tr>
<td align="left">LOAD_FAST</td>
<td align="right">11,700</td>
<td align="right">1.1%</td>
</tr>
<tr>
<td align="left">EXTENDED_ARG</td>
<td align="right">660</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>


</details>

### WITH_EXCEPT_START

<details>
<summary> Successors and predecessors for WITH_EXCEPT_START </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">PUSH_EXC_INFO</td>
<td align="right">4,080</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">4,080</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_FROM_DICT_OR_DEREF

<details>
<summary> Successors and predecessors for LOAD_FROM_DICT_OR_DEREF </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_LOCALS</td>
<td align="right">1,380</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">1,200</td>
<td align="right">87.0%</td>
</tr>
<tr>
<td align="left">LOAD_CONST_IMMORTAL</td>
<td align="right">180</td>
<td align="right">13.0%</td>
</tr>
</tbody>
</table>


</details>

### CLEANUP_THROW

<details>
<summary> Successors and predecessors for CLEANUP_THROW </summary>

<table>
<thead>
<tr>
<th align="left">Predecessors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CACHE</td>
<td align="right">480</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Successors</th>
<th align="right">Count</th>
<th align="right">Percentage</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">CALL_INTRINSIC_1</td>
<td align="right">480</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>


</details>

## Specialization stats

<details>
<summary> Specialization stats by family </summary>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">967,203,245</td>
<td align="right">20.7%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">3,660,718,855</td>
<td align="right">78.4%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">37,907,035</td>
<td align="right">0.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">718,597</td>
<td align="right">38.3%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">1,155,473</td>
<td align="right">61.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">subtract different types</td>
<td align="right">580,468</td>
<td align="right">50.2%</td>
</tr>
<tr>
<td align="left">multiply different types</td>
<td align="right">172,246</td>
<td align="right">14.9%</td>
</tr>
<tr>
<td align="left">add different types</td>
<td align="right">167,357</td>
<td align="right">14.5%</td>
</tr>
<tr>
<td align="left">remainder</td>
<td align="right">37,906</td>
<td align="right">3.3%</td>
</tr>
<tr>
<td align="left">floor divide</td>
<td align="right">33,315</td>
<td align="right">2.9%</td>
</tr>
<tr>
<td align="left">and int</td>
<td align="right">31,712</td>
<td align="right">2.7%</td>
</tr>
<tr>
<td align="left">add other</td>
<td align="right">23,966</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">rshift</td>
<td align="right">23,099</td>
<td align="right">2.0%</td>
</tr>
<tr>
<td align="left">lshift</td>
<td align="right">19,200</td>
<td align="right">1.7%</td>
</tr>
<tr>
<td align="left">xor</td>
<td align="right">18,320</td>
<td align="right">1.6%</td>
</tr>
<tr>
<td align="left">true divide different types</td>
<td align="right">18,260</td>
<td align="right">1.6%</td>
</tr>
<tr>
<td align="left">subtract other</td>
<td align="right">8,040</td>
<td align="right">0.7%</td>
</tr>
<tr>
<td align="left">true divide float</td>
<td align="right">7,120</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">power</td>
<td align="right">5,140</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">or</td>
<td align="right">4,614</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">multiply other</td>
<td align="right">2,560</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">true divide other</td>
<td align="right">1,140</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">and other</td>
<td align="right">970</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">and different types</td>
<td align="right">40</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_SLICE

<details>
<summary> specialization stats for BINARY_SLICE family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">99,085,080</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">1,218,265,089</td>
<td align="right">45.9%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">1,430,555,433</td>
<td align="right">53.9%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">3,377,729</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">65,080</td>
<td align="right">17.2%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">312,704</td>
<td align="right">82.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">array int</td>
<td align="right">154,460</td>
<td align="right">49.4%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">77,850</td>
<td align="right">24.9%</td>
</tr>
<tr>
<td align="left">list slice</td>
<td align="right">34,174</td>
<td align="right">10.9%</td>
</tr>
<tr>
<td align="left">buffer int</td>
<td align="right">27,061</td>
<td align="right">8.7%</td>
</tr>
<tr>
<td align="left">out of range</td>
<td align="right">12,740</td>
<td align="right">4.1%</td>
</tr>
<tr>
<td align="left">sequence int</td>
<td align="right">2,920</td>
<td align="right">0.9%</td>
</tr>
<tr>
<td align="left">tuple slice</td>
<td align="right">1,619</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">string slice</td>
<td align="right">1,100</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">buffer slice</td>
<td align="right">760</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">array slice</td>
<td align="right">20</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">79,660,165</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">
deopt
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">12,000</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">5,816,157,164</td>
<td align="right">97.4%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">77,000,790</td>
<td align="right">1.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">1,492,448</td>
<td align="right">98.7%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">20,240</td>
<td align="right">1.3%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">out of versions</td>
<td align="right">20,240</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">init not inline values</td>
<td align="right">20,240</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">init not simple</td>
<td align="right">180</td>
<td align="right">0.9%</td>
</tr>
<tr>
<td align="left">init not python</td>
<td align="right">40</td>
<td align="right">0.2%</td>
</tr>
</tbody>
</table>


</details>

### CALL_KW

<details>
<summary> specialization stats for CALL_KW family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">2,620</td>
<td align="right">57.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">1,924</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">0</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">144,324,697</td>
<td align="right">8.6%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">1,534,641,374</td>
<td align="right">91.3%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">1,125,502</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">24,616</td>
<td align="right">20.4%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">95,842</td>
<td align="right">79.6%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">different types</td>
<td align="right">25,673</td>
<td align="right">26.8%</td>
</tr>
<tr>
<td align="left">big int</td>
<td align="right">22,270</td>
<td align="right">23.2%</td>
</tr>
<tr>
<td align="left">float long</td>
<td align="right">15,282</td>
<td align="right">15.9%</td>
</tr>
<tr>
<td align="left">string</td>
<td align="right">7,040</td>
<td align="right">7.3%</td>
</tr>
<tr>
<td align="left">set</td>
<td align="right">6,661</td>
<td align="right">6.9%</td>
</tr>
<tr>
<td align="left">baseobject</td>
<td align="right">6,200</td>
<td align="right">6.5%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">6,133</td>
<td align="right">6.4%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">3,248</td>
<td align="right">3.4%</td>
</tr>
<tr>
<td align="left">bool</td>
<td align="right">1,455</td>
<td align="right">1.5%</td>
</tr>
<tr>
<td align="left">bytes</td>
<td align="right">1,280</td>
<td align="right">1.3%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">420</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">long float</td>
<td align="right">180</td>
<td align="right">0.2%</td>
</tr>
</tbody>
</table>


</details>

### CONTAINS_OP

<details>
<summary> specialization stats for CONTAINS_OP family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">172,644,178</td>
<td align="right">23.7%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">554,809,897</td>
<td align="right">76.1%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">1,249,640</td>
<td align="right">0.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">23,880</td>
<td align="right">32.3%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">49,972</td>
<td align="right">67.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">str</td>
<td align="right">28,060</td>
<td align="right">56.2%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">12,140</td>
<td align="right">24.3%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">5,861</td>
<td align="right">11.7%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">3,911</td>
<td align="right">7.8%</td>
</tr>
</tbody>
</table>


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">349,921,670</td>
<td align="right">15.4%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">1,787,322,802</td>
<td align="right">78.8%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">129,487,277</td>
<td align="right">5.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">2,443,455</td>
<td align="right">95.1%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">126,529</td>
<td align="right">4.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">dict items</td>
<td align="right">56,963</td>
<td align="right">45.0%</td>
</tr>
<tr>
<td align="left">enumerate</td>
<td align="right">21,324</td>
<td align="right">16.9%</td>
</tr>
<tr>
<td align="left">set</td>
<td align="right">11,482</td>
<td align="right">9.1%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">10,280</td>
<td align="right">8.1%</td>
</tr>
<tr>
<td align="left">seq iter</td>
<td align="right">8,240</td>
<td align="right">6.5%</td>
</tr>
<tr>
<td align="left">zip</td>
<td align="right">6,080</td>
<td align="right">4.8%</td>
</tr>
<tr>
<td align="left">dict values</td>
<td align="right">4,760</td>
<td align="right">3.8%</td>
</tr>
<tr>
<td align="left">ascii string</td>
<td align="right">2,360</td>
<td align="right">1.9%</td>
</tr>
<tr>
<td align="left">itertools</td>
<td align="right">2,320</td>
<td align="right">1.8%</td>
</tr>
<tr>
<td align="left">dict keys</td>
<td align="right">1,440</td>
<td align="right">1.1%</td>
</tr>
<tr>
<td align="left">reversed list</td>
<td align="right">720</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">map</td>
<td align="right">400</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">callable</td>
<td align="right">140</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">string</td>
<td align="right">20</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">644,898,709</td>
<td align="right">8.0%</td>
</tr>
<tr>
<td align="left">
deopt
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">1,112,300</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">6,905,101,170</td>
<td align="right">85.8%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">497,435,283</td>
<td align="right">6.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">9,354,540</td>
<td align="right">97.9%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">204,105</td>
<td align="right">2.1%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">overriding descriptor</td>
<td align="right">72,868</td>
<td align="right">35.7%</td>
</tr>
<tr>
<td align="left">method</td>
<td align="right">40,501</td>
<td align="right">19.8%</td>
</tr>
<tr>
<td align="left">mutable class</td>
<td align="right">34,203</td>
<td align="right">16.8%</td>
</tr>
<tr>
<td align="left">metaclass attribute</td>
<td align="right">17,441</td>
<td align="right">8.5%</td>
</tr>
<tr>
<td align="left">class method obj</td>
<td align="right">14,180</td>
<td align="right">6.9%</td>
</tr>
<tr>
<td align="left">overridden</td>
<td align="right">7,313</td>
<td align="right">3.6%</td>
</tr>
<tr>
<td align="left">non overriding descriptor</td>
<td align="right">4,642</td>
<td align="right">2.3%</td>
</tr>
<tr>
<td align="left">non object slot</td>
<td align="right">4,360</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">expected error</td>
<td align="right">2,460</td>
<td align="right">1.2%</td>
</tr>
<tr>
<td align="left">not managed dict</td>
<td align="right">700</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">builtin class method</td>
<td align="right">620</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">module attr not found</td>
<td align="right">540</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">out of versions</td>
<td align="right">400</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">class attr simple</td>
<td align="right">280</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">not in dict</td>
<td align="right">180</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">property</td>
<td align="right">40</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">7,286,361</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">
deopt
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">240</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">5,173,647,350</td>
<td align="right">99.9%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">15,080</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">33,140</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">0</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">36,751,409</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">160</td>
<td align="right">100.0%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">0</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>


</details>

### SEND

<details>
<summary> specialization stats for SEND family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">100,411,460</td>
<td align="right">17.9%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">458,962,624</td>
<td align="right">82.0%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">13,020</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">260</td>
<td align="right">1.0%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">25,420</td>
<td align="right">99.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">async generator send</td>
<td align="right">24,440</td>
<td align="right">96.1%</td>
</tr>
<tr>
<td align="left">list</td>
<td align="right">980</td>
<td align="right">3.9%</td>
</tr>
</tbody>
</table>


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">30,691,032</td>
<td align="right">3.0%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">935,094,077</td>
<td align="right">90.3%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">70,275,361</td>
<td align="right">6.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">2,512,190</td>
<td align="right">99.2%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">18,994</td>
<td align="right">0.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">class attr simple</td>
<td align="right">10,760</td>
<td align="right">56.6%</td>
</tr>
<tr>
<td align="left">not in dict</td>
<td align="right">3,120</td>
<td align="right">16.4%</td>
</tr>
<tr>
<td align="left">overriding descriptor</td>
<td align="right">2,300</td>
<td align="right">12.1%</td>
</tr>
<tr>
<td align="left">property</td>
<td align="right">820</td>
<td align="right">4.3%</td>
</tr>
<tr>
<td align="left">not managed dict</td>
<td align="right">490</td>
<td align="right">2.6%</td>
</tr>
<tr>
<td align="left">split dict</td>
<td align="right">480</td>
<td align="right">2.5%</td>
</tr>
<tr>
<td align="left">not in keys</td>
<td align="right">400</td>
<td align="right">2.1%</td>
</tr>
<tr>
<td align="left">overridden</td>
<td align="right">344</td>
<td align="right">1.8%</td>
</tr>
<tr>
<td align="left">method</td>
<td align="right">120</td>
<td align="right">0.6%</td>
</tr>
<tr>
<td align="left">no dict</td>
<td align="right">100</td>
<td align="right">0.5%</td>
</tr>
<tr>
<td align="left">non object slot</td>
<td align="right">60</td>
<td align="right">0.3%</td>
</tr>
</tbody>
</table>


</details>

### STORE_SLICE

<details>
<summary> specialization stats for STORE_SLICE family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">108,333,300</td>
<td align="right">100.0%</td>
</tr>
</tbody>
</table>


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">310,608,606</td>
<td align="right">41.8%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">432,434,328</td>
<td align="right">58.2%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">2,220</td>
<td align="right">0.0%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">860</td>
<td align="right">1.1%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">80,060</td>
<td align="right">98.9%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">array int</td>
<td align="right">48,800</td>
<td align="right">61.0%</td>
</tr>
<tr>
<td align="left">dict subclass no override</td>
<td align="right">18,160</td>
<td align="right">22.7%</td>
</tr>
<tr>
<td align="left">bytearray int</td>
<td align="right">5,200</td>
<td align="right">6.5%</td>
</tr>
<tr>
<td align="left">py simple</td>
<td align="right">4,240</td>
<td align="right">5.3%</td>
</tr>
<tr>
<td align="left">list slice</td>
<td align="right">2,500</td>
<td align="right">3.1%</td>
</tr>
<tr>
<td align="left">out of range</td>
<td align="right">940</td>
<td align="right">1.2%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">160</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">array slice</td>
<td align="right">60</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">174,169,556</td>
<td align="right">5.6%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">2,905,249,098</td>
<td align="right">92.6%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">57,487,810</td>
<td align="right">1.8%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">1,094,364</td>
<td align="right">79.3%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">286,010</td>
<td align="right">20.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">number</td>
<td align="right">121,607</td>
<td align="right">42.5%</td>
</tr>
<tr>
<td align="left">mapping</td>
<td align="right">64,914</td>
<td align="right">22.7%</td>
</tr>
<tr>
<td align="left">tuple</td>
<td align="right">64,043</td>
<td align="right">22.4%</td>
</tr>
<tr>
<td align="left">dict</td>
<td align="right">10,943</td>
<td align="right">3.8%</td>
</tr>
<tr>
<td align="left">bytes</td>
<td align="right">8,720</td>
<td align="right">3.0%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">5,815</td>
<td align="right">2.0%</td>
</tr>
<tr>
<td align="left">sequence</td>
<td align="right">5,261</td>
<td align="right">1.8%</td>
</tr>
<tr>
<td align="left">set</td>
<td align="right">4,347</td>
<td align="right">1.5%</td>
</tr>
<tr>
<td align="left">float</td>
<td align="right">360</td>
<td align="right">0.1%</td>
</tr>
</tbody>
</table>


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

<table>
<thead>
<tr>
<th align="left">Kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
deferred
<details>
<summary>ⓘ</summary>

Lists the number of "deferred" (i.e. not specialized) instructions executed.
</details>
</td>
<td align="right">101,198</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">
hit
<details>
<summary>ⓘ</summary>

Specialized instructions that complete.
</details>
</td>
<td align="right">1,328,422,543</td>
<td align="right">99.8%</td>
</tr>
<tr>
<td align="left">
miss
<details>
<summary>ⓘ</summary>

Specialized instructions that deopt.
</details>
</td>
<td align="right">2,547,700</td>
<td align="right">0.2%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Success</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Success</td>
<td align="right">50,820</td>
<td align="right">99.3%</td>
</tr>
<tr>
<td align="left">Failure</td>
<td align="right">382</td>
<td align="right">0.7%</td>
</tr>
</tbody>
</table>

<table>
<thead>
<tr>
<th align="left">Failure kind</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">sequence</td>
<td align="right">222</td>
<td align="right">58.1%</td>
</tr>
<tr>
<td align="left">other</td>
<td align="right">80</td>
<td align="right">20.9%</td>
</tr>
<tr>
<td align="left">iterator</td>
<td align="right">80</td>
<td align="right">20.9%</td>
</tr>
</tbody>
</table>


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>


All entries are execution counts. Should add up to the total number of
Tier 1 instructions executed.

<table>
<thead>
<tr>
<th align="left">Instructions</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
Basic
<details>
<summary>ⓘ</summary>

Instructions that are not and cannot be specialized, e.g. `LOAD_FAST`.
</details>
</td>
<td align="right">61,524,108,116</td>
<td align="right">57.4%</td>
</tr>
<tr>
<td align="left">
Not specialized
<details>
<summary>ⓘ</summary>

Instructions that could be specialized but aren't, e.g. `LOAD_ATTR`, `BINARY_SLICE`.
</details>
</td>
<td align="right">4,410,782,350</td>
<td align="right">4.1%</td>
</tr>
<tr>
<td align="left">
Specialized hits
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that complete.
</details>
</td>
<td align="right">40,365,794,635</td>
<td align="right">37.7%</td>
</tr>
<tr>
<td align="left">
Specialized misses
<details>
<summary>ⓘ</summary>

Specialized instructions, e.g. `LOAD_ATTR_MODULE` that deopt.
</details>
</td>
<td align="right">877,955,467</td>
<td align="right">0.8%</td>
</tr>
</tbody>
</table>

### Deferred by instruction

<details>
<summary> Breakdown of deferred (not specialized) instruction counts by family </summary>

<table>
<thead>
<tr>
<th align="left">Name</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">BINARY_SUBSCR</td>
<td align="right">1,218,265,089</td>
<td align="right">27.6%</td>
</tr>
<tr>
<td align="left">BINARY_OP</td>
<td align="right">967,203,245</td>
<td align="right">21.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR</td>
<td align="right">644,898,709</td>
<td align="right">14.6%</td>
</tr>
<tr>
<td align="left">FOR_ITER</td>
<td align="right">349,921,670</td>
<td align="right">7.9%</td>
</tr>
<tr>
<td align="left">STORE_SUBSCR</td>
<td align="right">310,608,606</td>
<td align="right">7.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL</td>
<td align="right">174,169,556</td>
<td align="right">4.0%</td>
</tr>
<tr>
<td align="left">CONTAINS_OP</td>
<td align="right">172,644,178</td>
<td align="right">3.9%</td>
</tr>
<tr>
<td align="left">COMPARE_OP</td>
<td align="right">144,324,697</td>
<td align="right">3.3%</td>
</tr>
<tr>
<td align="left">STORE_SLICE</td>
<td align="right">108,333,300</td>
<td align="right">2.5%</td>
</tr>
<tr>
<td align="left">SEND</td>
<td align="right">100,411,460</td>
<td align="right">2.3%</td>
</tr>
</tbody>
</table>


</details>

### Misses by instruction

<details>
<summary> Breakdown of misses (specialized deopts) instruction counts by family </summary>

<table>
<thead>
<tr>
<th align="left">Name</th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">LOAD_ATTR_INSTANCE_VALUE</td>
<td align="right">192,468,725</td>
<td align="right">21.9%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_METHOD_WITH_VALUES</td>
<td align="right">140,945,358</td>
<td align="right">16.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_SLOT</td>
<td align="right">74,450,178</td>
<td align="right">8.5%</td>
</tr>
<tr>
<td align="left">FOR_ITER_LIST</td>
<td align="right">64,729,797</td>
<td align="right">7.4%</td>
</tr>
<tr>
<td align="left">FOR_ITER_TUPLE</td>
<td align="right">64,704,260</td>
<td align="right">7.4%</td>
</tr>
<tr>
<td align="left">STORE_ATTR_INSTANCE_VALUE</td>
<td align="right">61,950,620</td>
<td align="right">7.1%</td>
</tr>
<tr>
<td align="left">LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES</td>
<td align="right">55,757,724</td>
<td align="right">6.4%</td>
</tr>
<tr>
<td align="left">CALL_PY_EXACT_ARGS</td>
<td align="right">39,332,362</td>
<td align="right">4.5%</td>
</tr>
<tr>
<td align="left">TO_BOOL_NONE</td>
<td align="right">26,090,042</td>
<td align="right">3.0%</td>
</tr>
<tr>
<td align="left">TO_BOOL_ALWAYS_TRUE</td>
<td align="right">25,513,878</td>
<td align="right">2.9%</td>
</tr>
</tbody>
</table>


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>


This shows what fraction of calls to Python functions are inlined (i.e.
not having a call at the C level) and for those that are not, where the
call comes from.  The various categories overlap.

Also includes the count of frame objects created.

<table>
<thead>
<tr>
<th align="left"></th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Calls to PyEval_EvalDefault</td>
<td align="right">1,029,909,702</td>
<td align="right">25.1%</td>
</tr>
<tr>
<td align="left">Calls to Python functions inlined</td>
<td align="right">3,074,524,516</td>
<td align="right">74.9%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (total)</td>
<td align="right">1,029,909,702</td>
<td align="right">25.1%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (vector)</td>
<td align="right">498,181,297</td>
<td align="right">12.1%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (generator)</td>
<td align="right">531,728,405</td>
<td align="right">13.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (legacy)</td>
<td align="right">3,964,200</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function vectorcall)</td>
<td align="right">494,215,777</td>
<td align="right">12.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (build class)</td>
<td align="right">1,320</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (slot)</td>
<td align="right">111,902,943</td>
<td align="right">2.7%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (function ex)</td>
<td align="right">13,976,006</td>
<td align="right">0.3%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (api)</td>
<td align="right">132,088,194</td>
<td align="right">3.2%</td>
</tr>
<tr>
<td align="left">Calls via PyEval_EvalFrame (method)</td>
<td align="right">35,386,440</td>
<td align="right">0.9%</td>
</tr>
<tr>
<td align="left">Frame objects created</td>
<td align="right">44,436,655</td>
<td align="right">1.1%</td>
</tr>
<tr>
<td align="left">Frames pushed</td>
<td align="right">3,029,423,305</td>
<td align="right">73.8%</td>
</tr>
</tbody>
</table>


</details>

## Object stats

<details>
<summary> Allocations, frees and dict materializatons </summary>


Below, "allocations" means "allocations that are not from a freelist".
Total allocations = "Allocations from freelist" + "Allocations".

"Inline values" is the number of values arrays inlined into objects.

The cache hit/miss numbers are for the MRO cache, split into dunder and
other names.

<table>
<thead>
<tr>
<th align="left"></th>
<th align="right">Count</th>
<th align="right">Ratio</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Allocations from freelist</td>
<td align="right">5,364,820,062</td>
<td align="right">58.5%</td>
</tr>
<tr>
<td align="left">Frees to freelist</td>
<td align="right">5,364,969,742</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Allocations</td>
<td align="right">3,799,494,896</td>
<td align="right">41.5%</td>
</tr>
<tr>
<td align="left">Allocations to 512 bytes</td>
<td align="right">3,750,855,496</td>
<td align="right">40.9%</td>
</tr>
<tr>
<td align="left">Allocations to 4 kbytes</td>
<td align="right">38,367,620</td>
<td align="right">0.4%</td>
</tr>
<tr>
<td align="left">Allocations over 4 kbytes</td>
<td align="right">10,271,780</td>
<td align="right">0.1%</td>
</tr>
<tr>
<td align="left">Frees</td>
<td align="right">4,019,734,399</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Inline values</td>
<td align="right">78,383,894</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Interpreter mortal increfs</td>
<td align="right">38,788,351,975</td>
<td align="right">44.7%</td>
</tr>
<tr>
<td align="left">Interpreter mortal decrefs</td>
<td align="right">43,752,928,897</td>
<td align="right">42.9%</td>
</tr>
<tr>
<td align="left">Mortal increfs</td>
<td align="right">12,767,721,405</td>
<td align="right">14.7%</td>
</tr>
<tr>
<td align="left">Mortal decrefs</td>
<td align="right">16,412,595,025</td>
<td align="right">16.1%</td>
</tr>
<tr>
<td align="left">Interpreter immortal increfs</td>
<td align="right">20,493,960,233</td>
<td align="right">23.6%</td>
</tr>
<tr>
<td align="left">Interpreter immortal decrefs</td>
<td align="right">26,593,213,853</td>
<td align="right">26.1%</td>
</tr>
<tr>
<td align="left">Immortal increfs</td>
<td align="right">14,656,752,852</td>
<td align="right">16.9%</td>
</tr>
<tr>
<td align="left">Immortal decrefs</td>
<td align="right">15,290,085,254</td>
<td align="right">15.0%</td>
</tr>
<tr>
<td align="left">Materialize dict (on request)</td>
<td align="right">4,913,640</td>
<td align="right">6.3%</td>
</tr>
<tr>
<td align="left">Materialize dict (new key)</td>
<td align="right">121,320</td>
<td align="right">0.2%</td>
</tr>
<tr>
<td align="left">Materialize dict (too big)</td>
<td align="right">3,000</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Materialize dict (str subclass)</td>
<td align="right">0</td>
<td align="right">0.0%</td>
</tr>
<tr>
<td align="left">Method cache hits</td>
<td align="right">1,417,429,674</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Method cache misses</td>
<td align="right">36,819,818</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Method cache collisions</td>
<td align="right">41,427,857</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Method cache dunder hits</td>
<td align="right">1,444,464,188</td>
<td align="right"></td>
</tr>
<tr>
<td align="left">Method cache dunder misses</td>
<td align="right">5,383,355</td>
<td align="right"></td>
</tr>
</tbody>
</table>


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>


Collected/visits gives some measure of efficiency.

<table>
<thead>
<tr>
<th align="right">Generation</th>
<th align="right">Collections</th>
<th align="right">Objects collected</th>
<th align="right">Object visits</th>
<th align="right">Reachable from roots</th>
<th align="right">Not reachable from roots</th>
</tr>
</thead>
<tbody>
<tr>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
</tr>
<tr>
<td align="right">1</td>
<td align="right">53,380</td>
<td align="right">77,420,580</td>
<td align="right">1,670,768,922</td>
<td align="right">95,990,120</td>
<td align="right">133,658,360</td>
</tr>
<tr>
<td align="right">2</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
<td align="right">0</td>
</tr>
</tbody>
</table>


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>


</details>

## Rare events

<details>
<summary> Counts of rare/unlikely events </summary>

<table>
<thead>
<tr>
<th align="left">Event</th>
<th align="right">Count</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">
set class
<details>
<summary>ⓘ</summary>

Setting an object's class, `obj.__class__ = ...`
</details>
</td>
<td align="right">0</td>
</tr>
<tr>
<td align="left">
set bases
<details>
<summary>ⓘ</summary>

Setting the bases of a class, `cls.__bases__ = ...`
</details>
</td>
<td align="right">0</td>
</tr>
<tr>
<td align="left">
set eval frame func
<details>
<summary>ⓘ</summary>

Setting the PEP 523 frame eval function `_PyInterpreterState_SetFrameEvalFunc()`
</details>
</td>
<td align="right">0</td>
</tr>
<tr>
<td align="left">
builtin dict
<details>
<summary>ⓘ</summary>

Modifying the builtins, `__builtins__.__dict__[var] = ...`
</details>
</td>
<td align="right">0</td>
</tr>
<tr>
<td align="left">
func modification
<details>
<summary>ⓘ</summary>

Modifying a function, e.g. `func.__defaults__ = ...`, etc.
</details>
</td>
<td align="right">0</td>
</tr>
<tr>
<td align="left">
watched dict modification
<details>
<summary>ⓘ</summary>

A watched dict has been modified
</details>
</td>
<td align="right">0</td>
</tr>
<tr>
<td align="left">
watched globals modification
<details>
<summary>ⓘ</summary>

A watched `globals()` dict has been modified
</details>
</td>
<td align="right">0</td>
</tr>
</tbody>
</table>


</details>

## Meta stats

<details>
<summary> Meta statistics </summary>

<table>
<thead>
<tr>
<th align="left"></th>
<th align="right">Count</th>
</tr>
</thead>
<tbody>
<tr>
<td align="left">Number of data files</td>
<td align="right">1,440</td>
</tr>
</tbody>
</table>


</details>

---
Stats gathered on: 2024-12-15
