<template>
    <div class="container-fluid">
        <div class="row">

            <div class="col-xl-3 col-lg-3 col-md-12 col-sm-12 col-12 animated fadeIn p-2">
                <div class="card card-plain h-100 bg-white">
                    <div class="p-3">
                        <div class="row">
                            <div class="col-9 col-lg-8 col-md-8 col-sm-9">
                                <div>
                                    <h5 class="mb-0 text-capitalize font-weight-bold">
                                        <span id="product">{{ cummary['product'] }}</span>
                                    </h5>
                                    <p class="mb-0 text-sm">Product</p>
                                </div>
                            </div>
                            <div class="col-3 col-lg-4 col-md-4 col-sm-3 text-end">
                                <div class="icon icon-shape bg-primary shadow-sm float-end rounded-3">
                                    <!-- <img alt="" class="w-100 " src="../../Assets/img/icon.svg" /> -->
                                    <svg class="w-[48px] h-[48px] text-white dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="48" height="48" fill="currentColor" viewBox="0 0 24 24">
  <path d="M5 3a2 2 0 0 0-2 2v2a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2H5Zm14 18a2 2 0 0 0 2-2v-2a2 2 0 0 0-2-2h-4a2 2 0 0 0-2 2v2a2 2 0 0 0 2 2h4ZM5 11a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2v-6a2 2 0 0 0-2-2H5Zm14 2a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2h-4a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h4Z"/>
</svg>

                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="col-xl-3 col-lg-3 col-md-12 col-sm-12 col-12 animated fadeIn p-2">
                <div class="card card-plain h-100 bg-white">
                    <div class="p-3">
                        <div class="row">
                            <div class="col-9 col-lg-8 col-md-8 col-sm-9">
                                <div>
                                    <h5 class="mb-0 text-capitalize font-weight-bold">
                                        <span id="product">{{ cummary['category'] }}</span>
                                    </h5>
                                    <p class="mb-0 text-sm">Category</p>
                                </div>
                            </div>
                            <div class="col-3 col-lg-4 col-md-4 col-sm-3 text-end">
                                <div class="icon icon-shape bg-secondary shadow-sm float-end rounded-3">
                                    <svg class="w-[48px] h-[48px] text-white dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="48" height="48" fill="none" viewBox="0 0 24 24">
  <path fill="currentColor" d="M11.5039 3.13176c.3074-.17568.6848-.17568.9923 0l3.5554 2.0317L12 7.42604 7.94841 5.16346l3.55549-2.0317Zm-4.50388 3.7928L7 10.2768l-3.15822 1.8047 4.14118 2.205L11 12.5625V9.15832L7.00002 6.92456ZM3 13.8991v3.8152c0 .3588.19229.6902.50386.8682l3.49615 1.9978V16.029L3 13.8991Zm6.00001 6.6812L12 18.866l3 1.7143v-4.5714l-3-1.7143-2.99999 1.7142v4.5715Zm7.99999 0 3.4961-1.9978c.3116-.178.5039-.5094.5039-.8682v-3.8152l-4 2.1299v4.5513Zm3.1582-8.4988L17 10.2768V6.92457l-4 2.23375v3.40418l3.0171 1.724 4.1411-2.205Z"/>
</svg>

                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="col-xl-3 col-lg-3 col-md-12 col-sm-12 col-12 animated fadeIn p-2">
                <div class="card card-plain h-100 bg-white">
                    <div class="p-3">
                        <div class="row">
                            <div class="col-9 col-lg-8 col-md-8 col-sm-9">
                                <div>
                                    <h5 class="mb-0 text-capitalize font-weight-bold">
                                        <span id="product">{{ cummary['customer'] }}</span>
                                    </h5>
                                    <p class="mb-0 text-sm">Customer</p>
                                </div>
                            </div>
                            <div class="col-3 col-lg-4 col-md-4 col-sm-3 text-end">
                                <div class="icon icon-shape bg-info shadow-sm float-end rounded-3">
                                    <svg class="w-[48px] h-[48px] text-white dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="48" height="48" fill="none" viewBox="0 0 24 24">
  <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14.99 9H15M8.99 9H9m12 3a9 9 0 1 1-18 0 9 9 0 0 1 18 0ZM7 13c0 1 .507 2.397 1.494 3.216a5.5 5.5 0 0 0 7.022 0C16.503 15.397 17 14 17 13c0 0-1.99 1-4.995 1S7 13 7 13Z"/>
</svg>

                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="col-xl-3 col-lg-3 col-md-12 col-sm-12 col-12 animated fadeIn p-2">
                <div class="card card-plain h-100  bg-white">
                    <div class="p-3">
                        <div class="row">
                            <div class="col-9 col-lg-8 col-md-8 col-sm-9">
                                <div>
                                    <h5 class="mb-0 text-capitalize font-weight-bold">
                                        <span id="product">{{ cummary['invoice'] }}</span>
                                    </h5>
                                    <p class="mb-0 text-sm">Invoice</p>
                                </div>
                            </div>
                            <div class="col-3 col-lg-4 col-md-4 col-sm-3 text-end">
                                <div class="icon icon-shape bg-success shadow-sm float-end rounded-3">
                                    <svg class="w-[48px] h-[48px] text-white dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="48" height="48" fill="none" viewBox="0 0 24 24">
  <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 3v4a1 1 0 0 1-1 1H5m4 10v-2m3 2v-6m3 6v-3m4-11v16a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1V7.914a1 1 0 0 1 .293-.707l3.914-3.914A1 1 0 0 1 9.914 3H18a1 1 0 0 1 1 1Z"/>
</svg>

                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>


            <div class="col-xl-3 col-lg-3 col-md-12 col-sm-12 col-12 animated fadeIn p-2">
                <div class="card card-plain h-100 bg-white">
                    <div class="p-3">
                        <div class="row">
                            <div class="col-9 col-lg-8 col-md-8 col-sm-9">
                                <div>
                                    <h5 class="mb-0 text-capitalize font-weight-bold">
                                         <span id="product">{{ cummary['total'] }}</span>
                                    </h5>
                                    <p class="mb-0 text-sm">Total Sale</p>
                                </div>
                            </div>
                            <div class="col-3 col-lg-4 col-md-4 col-sm-3 text-end">
                                <div class="icon icon-shape bg-success shadow-sm float-end rounded-3">
                                    <svg class="w-[48px] h-[48px] text-white dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="48" height="48" fill="none" viewBox="0 0 24 24">
  <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 4h3a1 1 0 0 1 1 1v15a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h3m0 3h6m-5-4v4h4V3h-4Z"/>
</svg>

                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>


            <div class="col-xl-3 col-lg-3 col-md-12 col-sm-12 col-12 animated fadeIn p-2">
                <div class="card card-plain h-100  bg-white">
                    <div class="p-3">
                        <div class="row">
                            <div class="col-9 col-lg-8 col-md-8 col-sm-9">
                                <div>
                                    <h5 class="mb-0 text-capitalize font-weight-bold">
                                         <span id="product">{{ cummary['vat'] }}</span>
                                    </h5>
                                    <p class="mb-0 text-sm">Vat Collection</p>
                                </div>
                            </div>
                            <div class="col-3 col-lg-4 col-md-4 col-sm-3 text-end">
                                <div class="icon icon-shape bg-danger shadow-sm float-end rounded-3">
                                    <svg class="w-[48px] h-[48px] text-white dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="48" height="48" fill="currentColor" viewBox="0 0 24 24">
  <path fill-rule="evenodd" d="M9 2a1 1 0 0 0-1 1H6a2 2 0 0 0-2 2v15a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2h-2a1 1 0 0 0-1-1H9Zm1 2h4v2h1a1 1 0 1 1 0 2H9a1 1 0 0 1 0-2h1V4Zm5.707 8.707a1 1 0 0 0-1.414-1.414L11 14.586l-1.293-1.293a1 1 0 0 0-1.414 1.414l2 2a1 1 0 0 0 1.414 0l4-4Z" clip-rule="evenodd"/>
</svg>

                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>


            <div class="col-xl-3 col-lg-3 col-md-12 col-sm-12 col-12 animated fadeIn p-2">
                <div class="card card-plain h-100  bg-white">
                    <div class="p-3">
                        <div class="row">
                            <div class="col-9 col-lg-8 col-md-8 col-sm-9">
                                <div>
                                    <h5 class="mb-0 text-capitalize font-weight-bold">
                                         <span>{{ cummary['payable'] }}</span>
                                    </h5>
                                    <p class="mb-0 text-sm">Total Payable</p>
                                </div>
                            </div>
                            <div class="col-3 col-lg-4 col-md-4 col-sm-3 text-end">
                                <div class="icon icon-shape bg-success shadow-sm float-end rounded-3">
                                    <svg class="w-[48px] h-[48px] text-white dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="48" height="48" fill="currentColor" viewBox="0 0 24 24">
  <path d="M5 13.17a3.001 3.001 0 0 0 0 5.66V20a1 1 0 1 0 2 0v-1.17a3.001 3.001 0 0 0 0-5.66V4a1 1 0 0 0-2 0v9.17ZM11 20v-9.17a3.001 3.001 0 0 1 0-5.66V4a1 1 0 1 1 2 0v1.17a3.001 3.001 0 0 1 0 5.66V20a1 1 0 1 1-2 0Zm6-1.17V20a1 1 0 1 0 2 0v-1.17a3.001 3.001 0 0 0 0-5.66V4a1 1 0 1 0-2 0v9.17a3.001 3.001 0 0 0 0 5.66Z"/>
</svg>

                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="col-xl-3 col-lg-3 col-md-12 col-sm-12 col-12 animated fadeIn p-2">
                <div class="card card-plain h-100  bg-white">
                    <div class="p-3">
                        <div class="row">
                            <div class="col-9 col-lg-8 col-md-8 col-sm-9">
                                <div>
                                    <h5 class="mb-0 text-capitalize font-weight-bold">
                                         <span>{{ cummary['discount'] }}</span>
                                    </h5>
                                    <p class="mb-0 text-sm">Total Discount</p>
                                </div>
                            </div>
                            <div class="col-3 col-lg-4 col-md-4 col-sm-3 text-end">
                                <div class="icon icon-shape bg-warning shadow-sm float-end rounded-3">
                                    <svg class="w-[48px] h-[48px] text-white dark:text-white" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" width="48" height="48" fill="currentColor" viewBox="0 0 24 24">
  <path fill-rule="evenodd" d="M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10-4.477 10-10 10S2 17.523 2 12Zm5.757-1a1 1 0 1 0 0 2h8.486a1 1 0 1 0 0-2H7.757Z" clip-rule="evenodd"/>
</svg>

                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </div>
</template>

<script setup>
import { usePage } from '@inertiajs/vue3';

const page = usePage()
    const cummary = page.props.list
</script>

